# ALX ESLint config

## O que inclui?

- Standard config base;
- React plugin;
- JSX a11y plugin;
- Prettier;
- Import Helpers;

## Setup

1. Instale as dependências

```
npm i -D @ctrlmais/eslint-config
```

```
yarn add -D eslint @ctrlmais/eslint-config
```

2. Crie um arquivo `.eslintrc.json` e adicione a configuração:
```
{
  "extends": "@ctrlmais/eslint-config/react"
}
```

> Você também pode usar um `.eslintrc.js` em vez de JSON, se preferir.