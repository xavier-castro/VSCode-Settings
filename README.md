# VSCode-Settings
My VSCode settings for MacOS and my Windows partition

## Windows Setup
Updated 2/13/2019
```
{
    // General
    "workbench.settings.editor": "json",
    "editor.fontSize": 14,
    "editor.fontFamily": "'SF Mono'",
    "workbench.startupEditor": "readme",
    "workbench.editor.enablePreview": false,
    "workbench.colorTheme": "Civic",


    // Zen Mode
    "zenMode.centerLayout": false,
    "zenMode.hideTabs": false,
    "zenMode.fullScreen": false,

    // Terminal
    "terminal.integrated.shell.windows": "C:\\WINDOWS\\sysnative\\bash.exe",
    "terminal.integrated.fontFamily": "'SF Mono'",

    // John Papa Angular Essentials Settings
    "editor.codeLens": false,
    "editor.renderWhitespace": "none",
    "editor.autoIndent": true,
    // "editor.fontFamily": "Inconsolata, Fira code",
    "editor.formatOnPaste": false,
    "editor.formatOnType": true,
    "editor.letterSpacing": 1,
    "editor.tabSize": 2,
    "editor.wordWrap": "off",
    "workbench.iconTheme": "vscode-seedling-icon-theme",

    // John Papa Angular Essentials File Settings
    "files.autoSave": "afterDelay",
    "files.autoSaveDelay": 2000,
    "files.exclude": {
        "**/.git": true,
        "**/.DS_Store": true,
        "**/*.js": {
            "when": "$(basename).ts"
        },
        "**/*.js.map": {
            "when": "$(basename)"
        }
    },
    "files.hotExit": "onExit",
    "files.defaultLanguage": "typescript",
    "files.trimTrailingWhitespace": true,

    // John Papa Angular Essentials Prettier settings
    "prettier.singleQuote": true,
    "prettier.printWidth": 100,

    // FILTER

}
```
