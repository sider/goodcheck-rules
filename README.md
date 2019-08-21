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
  - https://raw.githubusercontent.com/sider/goodcheck-rules/master/rules/typo.yml
```

For more details, please see [the Goodcheck documentation](https://github.com/sider/goodcheck#importing-rules).

## License

[MIT](LICENSE) © Sider
