# TODO before starting

    - Install Docker https://docs.docker.com/get-docker/
    - Press CTRL + SHIFT + P
    - Type "Settings"
    - Open "Preferences: User Settings (JSON)"
    - Paste the following and save

```json
{
  "breadcrumbs.enabled": true,
  "breadcrumbs.filePath": "on",
  "breadcrumbs.symbolPath": "on",
  "editor.fontLigatures": true,
  "editor.detectIndentation": true,
  "editor.insertSpaces": true,
  "explorer.openEditors.visible": 0,
  "editor.acceptSuggestionOnEnter": "on",
  "editor.autoClosingQuotes": "never",
  "editor.autoSurround": "never",
  "editor.bracketPairColorization.enabled": true,
  "editor.cursorStyle": "line",
  "editor.formatOnPaste": true,
  "editor.formatOnSave": true,
  "editor.minimap.renderCharacters": false,
  "editor.minimap.maxColumn": 200,
  "editor.minimap.showSlider": "always",
  "editor.renderWhitespace": "all",
  "editor.smoothScrolling": true,
  "editor.cursorBlinking": "phase",
  "editor.cursorSmoothCaretAnimation": true,
  "explorer.sortOrder": "type",
  "files.trimFinalNewlines": true,
  "files.insertFinalNewline": true,
  "files.trimTrailingWhitespace": true,
  "indentRainbow.excludedLanguages": ["plaintext"],
  "python.formatting.provider": "none",
  "python.linting.flake8Enabled": true,
  "python.languageServer": "Pylance",
  "python.analysis.typeCheckingMode": "basic",
  "telemetry.telemetryLevel": "off",
  "window.title": "${dirty}${activeEditorMedium}${separator}${rootName}${separator}${appName}",
  "workbench.editor.highlightModifiedTabs": true,
  "workbench.settings.enableNaturalLanguageSearch": false,
  "[c]": {
    "editor.rulers": [
      {
        "column": 79,
        "color": "#4d4c99"
      }
    ]
  },
  "[dockerfile]": {
    "editor.rulers": [
      {
        "column": 79,
        "color": "#0DB7ED"
      }
    ]
  },
  "[git-commit]": {
    "editor.rulers": [
      {
        "column": 50,
        "color": "#3E2C00"
      },
      {
        "column": 72,
        "color": "#F1502F"
      }
    ]
  },
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.rulers": [
      {
        "column": 100,
        "color": "#E34C26"
      },
      {
        "column": 120,
        "color": "#EBEBEB"
      }
    ]
  },
  "[css]": {
    "editor.tabSize": 2,
    "editor.rulers": [
      {
        "column": 79,
        "color": "#F0DB4F"
      },
      {
        "column": 100,
        "color": "#323330"
      }
    ]
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.rulers": [
      {
        "column": 79,
        "color": "#F0DB4F"
      },
      {
        "column": 100,
        "color": "#323330"
      }
    ]
  },
  "[typescript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode",
    "editor.tabSize": 2,
    "editor.rulers": [
      {
        "column": 79,
        "color": "#F0DB4F"
      },
      {
        "column": 100,
        "color": "#323330"
      }
    ]
  },
  "[python]": {
    "editor.tabSize": 4,
    "editor.rulers": [
      {
        "column": 79,
        "color": "#FFD43B"
      }
    ]
  },
  "workbench.sideBar.location": "right",
  "terminal.integrated.cursorBlinking": true,
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 2,
  "terminal.integrated.defaultProfile.linux": "bash",
  "security.workspace.trust.untrustedFiles": "newWindow",
  "git.confirmSync": false,
  "workbench.iconTheme": "gruvbox-material-icon-theme",
  "editor.suggestSelection": "first",
  "remote.SSH.remotePlatform": {
    "192.168.201.96": "linux"
  },
  "terminal.integrated.copyOnSelection": true,
  "terminal.integrated.defaultLocation": "view",
  "terminal.integrated.minimumContrastRatio": 5,
  "terminal.integrated.defaultProfile.windows": "Command Prompt",
  "terminal.integrated.fontFamily": "FiraCode Nerd Font, FiraCode NF",
  "workbench.startupEditor": "none",
  "jupyter.askForKernelRestart": false,
  "workbench.colorTheme": "Cobalt2",
  "dev.containers.defaultExtensions": [
    "ms-python.black-formatter",
    "dbaeumer.vscode-eslint",
    "esbenp.prettier-vscode",
    "ritwickdey.LiveServer",
    "oderwat.indent-rainbow",
    "ms-python.python",
    "ms-python.vscode-pylance",
    "ms-python.pylint",
    "christian-kohler.path-intellisense",
    "timonwong.shellcheck",
    "Remisa.shellman",
    "Fooxly.workspace",
    "christian-kohler.npm-intellisense"
  ],
  "liveServer.settings.donotShowInfoMsg": true,
  "[jsonc]": {
    "editor.defaultFormatter": "vscode.json-language-features"
  },
  "window.zoomLevel": 1,
  "material-icon-theme.files.associations": {
    "compose.yml": "docker",
    "compose.dev.yml": "docker"
  },
  "eslint.format.enable": true,
  "eslint.run": "onSave",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "prettier.singleQuote": true
}
```

    - Install all the following extensions

```bash
christian-kohler.npm-intellisense
christian-kohler.path-intellisense
dbaeumer.vscode-eslint
esbenp.prettier-vscode
Fooxly.workspace
jdinhlife.gruvbox
jeff-hykin.better-dockerfile-syntax
JonathanHarty.gruvbox-material-icon-theme
mhutchie.git-graph
ms-azuretools.vscode-docker
ms-python.black-formatter
ms-python.isort
ms-python.pylint
ms-python.python
ms-python.vscode-pylance
ms-toolsai.jupyter
ms-toolsai.jupyter-keymap
ms-toolsai.jupyter-renderers
ms-toolsai.vscode-jupyter-cell-tags
ms-toolsai.vscode-jupyter-slideshow
ms-vscode-remote.remote-containers
ms-vscode-remote.remote-ssh
ms-vscode-remote.remote-ssh-edit
ms-vscode-remote.remote-wsl
ms-vscode-remote.vscode-remote-extensionpack
ms-vscode.remote-explorer
oderwat.indent-rainbow
PKief.material-icon-theme
pranaygp.vscode-css-peek
Remisa.shellman
ritwickdey.LiveServer
timonwong.shellcheck
VisualStudioExptTeam.intellicode-api-usage-examples
VisualStudioExptTeam.vscodeintellicode
wesbos.theme-cobalt2
Zignd.html-css-class-completion

```

# To run project

```
bash up.sh -m dev
```
