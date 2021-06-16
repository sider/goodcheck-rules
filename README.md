# Goodcheck Rules

> A collection of useful [Goodcheck](https://github.com/sider/goodcheck) rules.

## Usage

Add this repository's URL to `import:` section in your project's `goodcheck.yml`.

For example:

```yaml
rules:
  - id: some_your_company_rule
    pattern: some_pattern
    message: Some message.

import:
  # Import all rules with a tag.
  - https://github.com/sider/goodcheck-rules/archive/refs/tags/v0.0.1.tar.gz
  # Import individual ruleset.
  - https://raw.githubusercontent.com/sider/goodcheck-rules/HEAD/rules/typo.yml
```

For more details, please see [the Goodcheck documentation](https://github.com/sider/goodcheck#importing-rules).

## Rulesets

- [Typo](rules/typo.yml)
- [Ruby](rules/ruby.yml)
- [Web](rules/web.yml)
- [GitHub](rules/github.yml)
