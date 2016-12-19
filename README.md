# Entoj Shareable ESLint Config
Shareable eslint config for the entoj project.

## Install
```bash
npm install eslint-config-entoj
```

## Usage
The eslint shareable configs can be used with the `extends` feature of `.eslintrc` files.

Learn more about [shareable configs](http://eslint.org/docs/developer-guide/shareable-configs) on the official ESLint website.

To use the Entoj shareable config, first run this:

```bash
npm install --save-dev eslint-config-entoj
```

Then, add this to your .eslintrc file:

```
{
  "extends": "entoj"
}
```

*Note: You can omit the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc` file.

## Learn more

For the full listing of rules visit the [wiki](https://github.com/pascaliske/eslint-config-entoj/wiki).

## License

MIT. Copyright &copy; [Pascal Iske](https://pascal-iske.de).
