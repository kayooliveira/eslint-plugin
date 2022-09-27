# Kayooliveira ESLint plugin

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import Resolver Plugin;
- TailwindCSS Plugin;
- 

## Setup

1. Install the dependencies
```
npm i -D eslint @kayooliveira/eslint-plugin
```

2. Create a `.eslintrc.json` file extending the plugin:
```
{
  "extends": "@kayooliveira/eslint-plugin/react"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.

> If you using NextJS, you need to install the '@next/eslint-plugin-next' plugin and add it to the extends array like this:
```
{
  "extends": [
    "@kayooliveira/eslint-plugin/react",
    "plugin:@next/next/recommended"
  ]
}
```

> Feel free to open an issue if you have any problem.


## License

MIT 




