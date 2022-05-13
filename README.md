# prettier-config-todomir

Uma [configuração compartilhável](https://prettier.io/docs/en/configuration.html#sharing-configurations)
para projetos utilizando **[Prettier](https://prettier.io)**.

## Instalação

```
npm install --save-dev prettier-config-todomir
```

_Essa configuração é apenas um template. Ela não instala o Prettier, ESLint ou quaisquer pacotes relacionados._

## Uso

Referencie no `package.json` usando a propriedade `prettier`:

```json
{
  "name": "meu-projeto",
  "prettier": "prettier-config-todomir",
  "devDependencies": {
    "prettier-config-todomir": "^1.0.1"
  }
}
```

Se não quiser utilizar no `package.json`, você pode usar de qualquer configuração abaixo para exportar uma string:

```jsonc
// `.prettierrc.json`
"prettier-config-todomir"
```

```javascript
// `prettier.config.js` or `.prettierrc.js`
module.exports = 'prettier-config-todomir';
```
