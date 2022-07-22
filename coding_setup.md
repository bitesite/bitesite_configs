# Prettier

## Required

1. Prettier should be installed in every project `yarn add --dev --exact prettier`
2. Every project should have its own `.prettierrc.js` (ideally we publish our own)
3. Every project should have its own `.prettierignore`
4. Every developer should install the Prettier VS Code Extension
5. Every project should have its own `.vscode/settings.json` which should include

```
{
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.formatOnSave": true
  }
}
```

## Recommended


# ESLint

1. Prettier should be installed in every project `yarn add --dev --exact eslint`
2. Every project should have its own `.eslintrc.js` (ideally we publish our own extension, ours would extend "eslint:recommended", "plugin:react/recommended", "prettier")

As a result: We would not set up ESLint as the formatter (that would be handled by prettier)
