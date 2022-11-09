# ctrl + ESLint config

## O que inclui?

- Standard config base;
- React plugin;
- JSX a11y plugin;
- Prettier;
- Import Helpers;

## Setup

1. Instale as dependências

```
npm i -D eslint @ctrlmais/eslint-config
```

```
yarn add -D eslint @ctrlmais/eslint-config
```

2. Crie um arquivo `.eslintrc.json` e adicione a configuração:
```bash
{
  # Se estiver usando React
  "extends": "@ctrlmais/eslint-config/react"

  # Se estiver usando Node
  "extends": "@ctrlmais/eslint-config/node"
}
```

> Você também pode usar um `.eslintrc.js` em vez de JSON, se preferir.