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
* [ESDoc MDN](https://marketplace.visualstudio.com/items?itemName=samundrak.esdoc-mdn)
	* This extension lets you quickly bring up helpful MDN documentation in the editor by typing `//mdn [object.property]` for example.
* [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
	* Hosts a local server in your workspace for you to preview your webpages on in VSC!
* [HTML CSS Support](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
	* HTML `id` and `class` attribute completion for Visual Studio Code.

### GitHub

* [Gist](https://marketplace.visualstudio.com/items?itemName=kenhowardpdx.vscode-gist)
	* Access your GitHub Gists within Visual Studio Code.
* [GistPad](https://marketplace.visualstudio.com/items?itemName=vsls-contrib.gistfs)
	* GistPad is a Visual Studio Code extension that allows you to edit GitHub [Gists](https://gist.github.com/ "https://gist.github.com/") and repositories from the comfort of your favorite editor
* [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory)
	* View git log, file history, compare branches or commits
* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore)
	* Lets you pull .gitignore templates from [https://github.com/github/gitignore](https://github.com/github/gitignore)
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens)
	* Supercharge Git within VS Code
* [Open in GitHub, Bitbucket, Gitlab, VisualStudio.com](https://marketplace.visualstudio.com/items?itemName=ziyasal.vscode-open-in-github)
	* Open in GitHub, Bitbucket, Gitlab, VisualStudio.com

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
* [Image Preview](https://marketplace.visualstudio.com/items?itemName=kisstkondoros.vscode-gutter-preview)
	* Shows image preview in the gutter and on hover
* [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
  * Change the font size with keyboard shortcuts.
* [WakaTime](https://marketplace.visualstudio.com/items?itemName=WakaTime.vscode-wakatime)
	* Metrics, insights, and time tracking automatically generated from your programming activity.

# Settings

```json
{

"[c]": {

"editor.defaultFormatter": "ms-vscode.cpptools"

},

"background.customImages": [

"https://static.wikia.nocookie.net/deadspace/images/7/7d/DS3_Erf.png/revision/latest/scale-to-width-down/512?cb=20130217174526"

],

"background.loop": false,

"background.style": {

"background-position": "125% 190%",

"background-repeat": "no-repeat",

"content": "''",

"height": "100%",

"opacity": 0.5,

"pointer-events": "none",

"position": "absolute",

"width": "100%",

"z-index": "99999"

},

"background.useDefault": false,

"background.useFront": false,

"better-comments.highlightPlainText": true,

"bracketPairColorizer.depreciation-notice": false,

"cSpell.allowCompoundWords": true,

"cSpell.ignorePaths": [

"node_modules", // this will ignore anything the node_modules directory

"**/node_modules", // the same for this one

"**/node_modules/**", // the same for this one

"node_modules/**", // Doesn't currently work due to how the current working directory is determined.

"vscode-extension", //

".git", // Ignore the .git directory

"*.dll", // Ignore all .dll files.

"**/*.dll" // Ignore all .dll files

],

"code-runner.customCommand": "echo Hello, world!",

"codesnap.backgroundColor": "black",

"codesnap.realLineNumbers": true,

"codesnap.showLineNumbers": true,

"codesnap.showWindowControls": true,

"codesnap.showWindowTitle": true,

"codesnap.shutterAction": "copy",

"codesnap.target": "window",

"csharp.semanticHighlighting.enabled": true,

"csharp.suppressHiddenDiagnostics": false,

"debug.onTaskErrors": "debugAnyway",

"diffEditor.codeLens": true,

"editor.acceptSuggestionOnEnter": "smart",

"editor.accessibilitySupport": "off",

"editor.cursorBlinking": "phase",

"editor.cursorSmoothCaretAnimation": true,

"editor.cursorStyle": "line-thin",

"editor.cursorWidth": 92,

"editor.defaultFormatter": "esbenp.prettier-vscode",

"editor.find.autoFindInSelection": "always",

"editor.find.globalFindClipboard": true,

"editor.fontFamily": "Fira Code",

"editor.fontLigatures": true,

"editor.fontWeight": "600",

"editor.formatOnType": true,

"editor.inlineSuggest.enabled": true,

"editor.linkedEditing": true,

"editor.minimap.enabled": false,

"editor.minimap.maxColumn": 50,

"editor.minimap.scale": 3,

"editor.minimap.showSlider": "always",

"editor.minimap.size": "fit",

"editor.quickSuggestions": {

"comments": "on",

"other": "on",

"strings": "on"

},

"editor.renderLineHighlight": "all",

"editor.renderWhitespace": "boundary",

"editor.smoothScrolling": true,

"editor.wordWrap": "on",

"editor.wordWrapColumn": 60,

"emojisense.languages": {

"javascript": false,

"json": true,

"markdown": true,

"plaintext": false,

"scminput": true // language used in the source control commit message box

},

"errorLens.delay": 100,

"errorLens.enabledDiagnosticLevels": [

"hint",

"warning",

"error"

],

"errorLens.fontStyleItalic": true,

"errorLens.fontWeight": "500",

"errorLens.gutterIconSet": "borderless",

"errorLens.gutterIconSize": "60%",

"errorLens.gutterIconsEnabled": true,

"errorLens.margin": "20ch",

"errorLens.messageEnabled": false,

"errorLens.statusBarColorsEnabled": true,

"errorLens.statusBarCommand": "goToLine",

"errorLens.statusBarMessageEnabled": true,

"errorLens.statusBarMessageType": "closestSeverity",

"explorer.compactFolders": false,

"explorer.confirmDelete": false,

"explorer.confirmDragAndDrop": false,

"explorer.fileNesting.enabled": true,

"files.exclude": {

"**/.DS_Store": false,

"**/.git": false,

"**/.hg": false,

"**/.svn": false,

"**/CVS": false,

"**/Thumbs.db": false

},

"foam.edit.linkReferenceDefinitions": "withExtensions",

"foam.openDailyNote.onStartup": false,

"gist.defaultPrivate": true,

"gistpad.comments.showThread": "always",

"gistpad.images.directoryName": "images",

"gistpad.images.pasteType": "file",

"git.autofetch": true,

"git.confirmSync": false,

"git.enableSmartCommit": false,

"github.gitAuthentication": false,

"html.format.indentInnerHtml": true,

"html.validate.styles": false,

"indentRainbow.excludedLanguages": [

"plaintext",

"markdown"

],

"javascript.updateImportsOnFileMove.enabled": "always",

"kite.showWelcomeNotificationOnStartup": false,

"liquid.format": true,

"livePreview.notifyOnOpenLooseFile": false,

"liveServer.settings.CustomBrowser": "chrome",

"liveServer.settings.donotShowInfoMsg": true,

"liveServer.settings.donotVerifyTags": true,

"liveServer.settings.fullReload": false,

"liveshare.anonymousGuestApproval": "accept",

"markdown-pdf.breaks": true,

"markdown-pdf.outputDirectoryRelativePathFile": true,

// "editor.fontFamily": "fantasy, Arial, cursive",

"markdownlint.config": {

"MD003": false,

"MD010": false,

"MD020": false,

"MD026": false,

"MD033": false,

"MD040": false,

"MD041": false

},

"markdownlint.focusMode": false,

"markdownlint.run": "onSave",

"material-icon-theme.folders.color": "#ffffff",

"material-icon-theme.folders.theme": "specific",

"material-icon-theme.hidesExplorerArrows": true,

"material-icon-theme.opacity": 1,

"path-intellisense.autoSlashAfterDirectory": true,

"path-intellisense.extensionOnImport": true,

"path-intellisense.showHiddenFiles": true,

"peacock.favoriteColors": [

{

"name": "Angular Red",

"value": "#dd0531"

},

{

"name": "Azure Blue",

"value": "#007fff"

},

{

"name": "Burlywood",

"value": "#deb887"

},

{

"name": "JavaScript Yellow",

"value": "#f9e64f"

},

{

"name": "Mandalorian Blue",

"value": "#1857a4"

},

{

"name": "Node Green",

"value": "#215732"

},

{

"name": "React Blue",

"value": "#61dafb"

},

{

"name": "Something Different",

"value": "#832561"

},

{

"name": "Svelte Orange",

"value": "#ff3d00"

},

{

"name": "Vue Green",

"value": "#42b883"

}

],

"prettier.enable": true,

"prettier.enableDebugLogs": true,

"prettier.quoteProps": "consistent",

"prettier.semi": true,

"prettier.singleQuote": false,

"prettier.useEditorConfig": true,

"problems.showCurrentInStatus": true,

"projectManager.git.baseFolders": [

"/Users/skyvi/braingoop",

"/Users/skyvi/Library/Application Support/"

],

"projectManager.groupList": true,

"projectManager.projectsLocation": "/Users/skyvi/saavv/.vscode",

"projectManager.showParentFolderInfoOnDuplicates": true,

"projectManager.sortList": "Recent",

"rpc.appName": "Code",

"rpc.buttonActiveLabel": "View Repository on GitHub",

"rpc.buttonEnabled": true,

"rpc.buttonInactiveLabel": "GitHub <3",

"rpc.buttonInactiveUrl": "https://github.com/saavv",

"rpc.checkIdle": false,

"rpc.detailsEditing": "Editing: {file_name} {problems}",

"rpc.detailsIdling": "No File Open",

"rpc.detailsViewing": "Viewing: {file_name}",

"rpc.enabled": true,

"rpc.idleTimeout": 600,

"rpc.lowerDetailsEditing": "{full_dir_name}",

"rpc.lowerDetailsViewing": "{full_dir_name}",

"rpc.removeElapsedTime": false,

"security.workspace.trust.untrustedFiles": "open",

"terminal.integrated.defaultProfile.osx": "bash",

"terminal.integrated.enableMultiLinePasteWarning": false,

"terminal.integrated.profiles.osx": {

"bash": {

"args": [

"-l"

],

"icon": "terminal-bash",

"path": "bash"

},

"bash (2)": {

"path": "/bin/bash"

},

"fish": {

"args": [

"-l"

],

"path": "fish"

},

"pwsh": {

"icon": "terminal-powershell",

"path": "pwsh"

},

"tmux": {

"icon": "terminal-tmux",

"path": "tmux"

},

"zsh": {

"args": [

"-l"

],

"path": "zsh"

}

},

"todo-tree.filtering.includeHiddenFiles": true,

"vscode-edge-devtools.autoAttachViaDebuggerForEdge": false,

"vscode-edge-devtools.headless": true,

"vscode-edge-devtools.pathMapping": {

"/": "${workspaceFolder}"

},

"window.openFilesInNewWindow": "on",

"workbench.colorTheme": "GitHub Dark Mode",

"workbench.editor.closeOnFileDelete": true,

"workbench.editor.untitled.hint": "hidden",

"workbench.editorAssociations": {

"*.jpeg": "magickImageReader.readImage",

"*.png": "magickImageReader.readImage",

"*.psd": "luna.editor",

"*.xcf": "luna.editor"

},

"workbench.iconTheme": "material-icon-theme",

"workbench.tree.indent": 10,

"workbench.tree.renderIndentGuides": "always",

"workbench.view.alwaysShowHeaderActions": true

}
```

# Keybindings

```json
// Place your key bindings in this file to override the defaults
[
    {
        "key": "cmd+b",
        "command": "-markdown.extension.editing.toggleBold",
        "when": "editorTextFocus && !editorReadonly && editorLangId == 'markdown'"
    },
    {
        "key": "ctrl+cmd+-",
        "command": "fontshortcuts.decreaseEditorFontSize",
        "when": "editorFocus"
    },
    {
        "key": "cmd+-",
        "command": "-fontshortcuts.decreaseEditorFontSize",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+cmd+-",
        "command": "fontshortcuts.decreaseTerminalFontSize",
        "when": "terminalFocus"
    },
    {
        "key": "cmd+-",
        "command": "-fontshortcuts.decreaseTerminalFontSize",
        "when": "terminalFocus"
    },
    {
        "key": "ctrl+cmd+=",
        "command": "fontshortcuts.increaseEditorFontSize",
        "when": "editorFocus"
    },
    {
        "key": "cmd+=",
        "command": "-fontshortcuts.increaseEditorFontSize",
        "when": "editorFocus"
    },
    {
        "key": "ctrl+cmd+=",
        "command": "fontshortcuts.increaseTerminalFontSize",
        "when": "terminalFocus"
    },
    {
        "key": "cmd+=",
        "command": "-fontshortcuts.increaseTerminalFontSize",
        "when": "terminalFocus"
    }
]
```
