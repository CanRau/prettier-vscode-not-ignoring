The issue is related to Prettier not yet supporting `handlebars`

My comment in prettier-vscode https://github.com/prettier/prettier-vscode/issues/1188#issuecomment-573811087

Quick fix until Prettier adds .hbs support

```
"[handlebars]": {
        "editor.formatOnSave": false,
        "editor.formatOnPaste": false
}
```

Related
https://github.com/prettier/prettier/issues/5340
https://github.com/prettier/prettier-vscode/issues/323
