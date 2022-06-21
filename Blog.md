# VS Code Settings

Getting started with Visual Studio Code or looking for...?

<details>
  <summary>Preview</summary>
<img alt="VSC preview" src="https://cdn.cacher.io/attachments/u/3g4bnueubwgp3/N04-EA4BkAY_IUkFN5Oyr9BVaV2751MV/Screen_Shot_2022-06-21_at_2.37.13_AM.png"/>

<img alt="Icons" src="https://cdn.cacher.io/attachments/u/3g4bnueubwgp3/78pgBBu3Lh93b0o9GIiGYhVdt_dhYPTh/Screen_Shot_2022-06-21_at_2.56.54_AM.png"/>
</details>

# Font

* [Fira Code](https://github.com/tonsky/FiraCode)

# Extensions

See my full list of extensions [here](https://gist.github.com/DoctorBraingoop/dd07009aa34b89a637bdf23a918f1cfb)

## Themes/Color/Icons

* Current theme:
  * [GitHub Dark Mode ♥️](https://marketplace.visualstudio.com/items?itemName=GitHub.github-vscode-theme)
  * [indent-rainbow](https://marketplace.visualstudio.com/items?itemName=oderwat.indent-rainbow)
	  * Makes indentation easier to read
* Icons:
  * [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme)

## Workflow

* [Auto Close Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-close-tag)
  * Automatically add HTML/XML close tag
* [Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)
  * Automatically rename paired HTML/XML tag
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.
* [Foam Research](https://marketplace.visualstudio.com/items?itemName=foam.foam-vscode)
  * note-taking tool that lives within VS Code, which means you can pair it with your favorite extensions for a great editing experience.
* [Better Comments](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)
  * Better Comments extension will help you create more human-friendly comments in your code
* [Code Runner](https://marketplace.visualstudio.com/items?itemName=formulahendry.code-runner)
  * Run code snippet or code file for multiple languages: **C, C++, Java, JavaScript, PHP, Python, Perl,** e.c.t.
* [advanced-new-file](https://marketplace.visualstudio.com/items?itemName=patbenatar.advanced-new-file)
	* Create files anywhere in your workspace from the keyboard
* [Error Lens](https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens)
	* Error Lens turbo-charges language diagnostic features
* [ESDoc MDN]()
	* This extension lets you quickly bring up helpful MDN documentation in the editor by typing `//mdn [object.property]` for example.
* [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
	* Hosts a local server in your workspace for you to preview your webpages on in VSC!


### GitHub
* [Gist](https://marketplace.visualstudio.com/items?itemName=kenhowardpdx.vscode-gist)
	* Access your GitHub Gists within Visual Studio Code.
* [GistPad]()
	* GistPad is a Visual Studio Code extension that allows you to edit GitHub [Gists](https://gist.github.com/ "https://gist.github.com/") and repositories from the comfort of your favorite editor
* [Git History]()
	* View git log, file history, compare branches or commits
* [gitignore]()
	* Lets you pull .gitignore templates from [https://github.com/github/gitignore](https://github.com/github/gitignore)
* [GitLens]()
	* Supercharge Git within VS Code



## Style/Formatting

* [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
  * Integrates ESLint JS
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
  * Automatically format javascript, JSON, CSS, Sass, and HTML files.
* [Color Highlight](https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight)
	* This extension styles css/web colors found in your document.


## Useful/Extra

* [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)
  * Display inline the size of the required/imported package
* [VS Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
  * Collaborative editing, debugging, and more inside VS Code
* [npm Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.npm-intellisense)
  * Autocompletes npm modules in import/require statements
* [Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)
  * Autocompletes filenames
* [Image Preview]()
	* Shows image preview in the gutter and on hover


# Settings

```json
{
  "search.exclude": {
    "**/node_modules": true,
    "**/bower_components": true,
    "**/*.code-search": true
  },
  "search.useIgnoreFiles": false,
  "explorer.openEditors.visible": 0,
  "editor.snippetSuggestions": "top",
  "emmet.showAbbreviationSuggestions": false,
  "editor.multiCursorModifier": "ctrlCmd",
  "editor.formatOnPaste": false,
  "workbench.colorTheme": "Just Black",
  "workbench.iconTheme": "vscode-icons",
  "editor.fontLigatures": true,
  "terminal.integrated.fontSize": 24,
  "files.autoSave": "off",
  "editor.fontFamily": "Anonymous Pro",
  "markdown.preview.fontSize": 36,
  "editor.tabSize": 2,
  "editor.detectIndentation": true,
  "editor.minimap.enabled": false,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "eslint.enable": true,
  "eslint.validate": ["vue", "react", "typescript", "html", "javascript"],
  "workbench.startupEditor": "newUntitledFile",
  "editor.suggestSelection": "first",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveshare.featureSet": "insiders",
  "[vue]": {
    "editor.defaultFormatter": "Vue.volar"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "[typescriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "liveshare.anonymousGuestApproval": "accept",
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "workbench.colorCustomizations": {},
  "[scss]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascriptreact]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "comment.block"
        ],
        "settings": {
          "fontStyle": "italic",
          "foreground": "#ff1493"
        }
      },
      {
        "scope": [
          "keyword.operator.logical",
          "keyword.operator.arithmetic",
          "keyword.operator.assignment",
          "keyword.operator.bitwise"
        ],
        "settings": {
          "fontStyle": ""
        }
      }
    ]
  },
  "git.autofetch": true,
  "editor.lineHeight": 0,
  "editor.fontSize": 17,
  "window.zoomLevel": 2,
  "vsicons.dontShowNewVersionMessage": true,
  "bracketPairColorizer.depreciation-notice": false,
  "extensions.ignoreRecommendations": true
}
```

# Keybindings

```json
[
  {
    "key": "cmd+1",
    "command": "workbench.action.openEditorAtIndex1"
  },
  {
    "key": "ctrl+1",
    "command": "-workbench.action.openEditorAtIndex1"
  },
  {
    "key": "cmd+2",
    "command": "workbench.action.openEditorAtIndex2"
  },
  {
    "key": "ctrl+2",
    "command": "-workbench.action.openEditorAtIndex2"
  },
  {
    "key": "cmd+3",
    "command": "workbench.action.openEditorAtIndex3"
  },
  {
    "key": "ctrl+3",
    "command": "-workbench.action.openEditorAtIndex3"
  },
  {
    "key": "cmd+4",
    "command": "workbench.action.openEditorAtIndex4"
  },
  {
    "key": "ctrl+4",
    "command": "-workbench.action.openEditorAtIndex4"
  },
  {
    "key": "cmd+5",
    "command": "workbench.action.openEditorAtIndex5"
  },
  {
    "key": "ctrl+5",
    "command": "-workbench.action.openEditorAtIndex5"
  },
  {
    "key": "cmd+6",
    "command": "workbench.action.openEditorAtIndex6"
  },
  {
    "key": "ctrl+6",
    "command": "-workbench.action.openEditorAtIndex6"
  },
  {
    "key": "cmd+7",
    "command": "workbench.action.openEditorAtIndex7"
  },
  {
    "key": "ctrl+7",
    "command": "-workbench.action.openEditorAtIndex7"
  },
  {
    "key": "cmd+8",
    "command": "workbench.action.openEditorAtIndex8"
  },
  {
    "key": "ctrl+8",
    "command": "-workbench.action.openEditorAtIndex8"
  },
  {
    "key": "cmd+9",
    "command": "workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+9",
    "command": "-workbench.action.openEditorAtIndex9"
  },
  {
    "key": "ctrl+1",
    "command": "workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "cmd+1",
    "command": "-workbench.action.focusFirstEditorGroup"
  },
  {
    "key": "ctrl+3",
    "command": "workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "cmd+3",
    "command": "-workbench.action.focusThirdEditorGroup"
  },
  {
    "key": "ctrl+6",
    "command": "workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "cmd+6",
    "command": "-workbench.action.focusSixthEditorGroup"
  },
  {
    "key": "ctrl+7",
    "command": "workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "cmd+7",
    "command": "-workbench.action.focusSeventhEditorGroup"
  },
  {
    "key": "ctrl+2",
    "command": "workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "cmd+2",
    "command": "-workbench.action.focusSecondEditorGroup"
  },
  {
    "key": "ctrl+4",
    "command": "workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "cmd+4",
    "command": "-workbench.action.focusFourthEditorGroup"
  },
  {
    "key": "ctrl+5",
    "command": "workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "cmd+5",
    "command": "-workbench.action.focusFifthEditorGroup"
  },
  {
    "key": "ctrl+8",
    "command": "workbench.action.focusEighthEditorGroup"
  },
  {
    "key": "cmd+8",
    "command": "-workbench.action.focusEighthEditorGroup"
  }
]
```
