# VSCode-Settings

My VSCode settings for MacOS and my Windows partition

## MacOS Setup

Updated 2/15/2019

```
{
    // General Settings
    "editor.wordWrap": "on",
    "files.defaultLanguage": "markdown",
    "workbench.settings.editor": "json",
    "workbench.fontAliasing": "auto",
    "editor.minimap.enabled": true,
    "vsicons.projectDetection.autoReload": true,
    "editor.fontFamily": "SF Mono",
    "editor.fontLigatures": true,
    "editor.fontSize": 14,
    "workbench.editor.enablePreview": false,

    // Angular Essentials Addon Settings
    "editor.codeLens": false,
    "editor.renderWhitespace": "none",
    "editor.autoIndent": true,
    "editor.formatOnPaste": false,
    "editor.formatOnType": true,
    "editor.letterSpacing": 1,
    "editor.tabSize": 2,
    "prettier.singleQuote": true,
    "prettier.printWidth": 100,

    // GIT
    "git.autofetch": true,
    "git.enableSmartCommit": true,

    // GitLens
    "gitlens.currentLine.enabled": false,
    "gitlens.hovers.enabled": false,

    // Zen Mode Changes
    "zenMode.fullScreen": false,
    "zenMode.hideTabs": false,
    "zenMode.centerLayout": false,

    // ESLint
    "eslint.run": "onType",
    "prettier.eslintIntegration": true,
    "workbench.iconTheme": "material-icon-theme",
    "workbench.startupEditor": "none",

    // Better Comments
    "better-comments.tags": [
        {
            "tag": "!",
            "color": "#FF2D00",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "?",
            "color": "#3498DB",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "//",
            "color": "#474747",
            "strikethrough": true,
            "backgroundColor": "transparent"
        },
        {
            "tag": "todo",
            "color": "#FF8C00",
            "strikethrough": false,
            "backgroundColor": "transparent"
        },
        {
            "tag": "*",
            "color": "#98C379",
            "strikethrough": false,
            "backgroundColor": "transparent"
        }
    ],
    "window.zoomLevel": 0,
    "git.confirmSync": false,
    "codestream.email": "xavier@augmenteddestiny.com",
    "workbench.colorTheme": "Civic",
}
```

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
