# react-ts-dev-conf

Development settings for using Typescript, React, webpack.

## Dependencies installation

- TypeScript
- React
- webpack
- ESLint + airbnb
- ESLint + TypeScript
- Prettier

### TypeScript

```sh
npm install --save-dev typescript ts-loader
```

### React

```sh
npm install react react-dom
npm install --save-dev @types/react @types/react-dom
```

### webpack

```sh
npm install --save-dev webpack webpack-cli webpack-dev-server
```

### ESLint + airbnb

Checking dependencies of eslint-config-airbnb.

```sh
npm info "eslint-config-airbnb@latest" peerDependencies

{
  eslint: '^5.16.0 || ^6.8.0 || ^7.2.0',
  'eslint-plugin-import': '^2.21.2',
  'eslint-plugin-jsx-a11y': '^6.3.0',
  'eslint-plugin-react': '^7.20.0',
  'eslint-plugin-react-hooks': '^4 || ^3 || ^2.3.0 || ^1.7.0'
}
```

Then installing dependencies and eslint-config-airbnb.

```sh
npm install --save-dev eslint@7.2.0 eslint-plugin-import@2.21.2 eslint-plugin-jsx-a11y@6.3.0 eslint-plugin-react@7.20.0 eslint-plugin-react-hooks@4 eslint-config-airbnb
```

### ESLint + TypeScript

```sh
npm install --save-dev eslint @typescript-eslint/parser @typescript-eslint/eslint-plugin @typescript-eslint/typescript-estree
```

### Prettier

```sh
npm install --save-dev prettier eslint-config-prettier eslint-plugin-prettier
```
