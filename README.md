```json
{
  "editor.fontFamily": "Roboto",
  "editor.fontLigatures": true,
  "editor.formatOnSave": true,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "breadcrumbs.enabled": false, // file path
  "editor.minimap.enabled": false, //on right side
  "editor.tabSize": 2,
  "editor.fontSize": 13,
  "editor.lineNumbers": "on",
  "explorer.confirmDragAndDrop": false,
  "editor.wordWrap": "on",
  "explorer.confirmDelete": false,
  "reactSnippets.settings.importReactOnTop": false,
  "editor.cursorBlinking": "expand",
  "editor.find.cursorMoveOnType": false,
  "editor.cursorSmoothCaretAnimation": "on",
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "editor.lineHeight": 22,
  // "terminal.integrated.enableMultiLinePasteWarning": false,
  "git.openRepositoryInParentFolders": "never",
  "workbench.iconTheme": "material-icon-theme",
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.accessibilitySupport": "off",
  "terminal.integrated.env.windows": {},
  "git.autofetch": true,
  "workbench.statusBar.visible": false, //bottom bar
  "workbench.layoutControl.enabled": false, //top bar
  "window.commandCenter": false, //top second bar
  "window.zoomLevel": 2,
  "editor.inlineSuggest.suppressSuggestions": true,
  "terminal.integrated.profiles.linux": {
    "bash": {
      "path": "bash",
      "icon": "terminal-bash"
    },
    "zsh": {
      "path": "zsh"
    },
    "fish": {
      "path": "fish"
    },
    "tmux": {
      "path": "tmux",
      "icon": "terminal-tmux"
    },
    "pwsh": {
      "path": "pwsh",
      "icon": "terminal-powershell"
    }
  },
  "terminal.integrated.fontFamily": "monospace",
  "workbench.activityBar.location": "hidden", //Explorer|Files... left side col
  "workbench.colorCustomizations": {
    "editor.background": "#1e1e1e", // Dark grey
    "editor.foreground": "#dcdcdc" // Light grey for general text
  },

  "editor.tokenColorCustomizations": {
    "textMateRules": [
      {
        "scope": "keyword",
        "settings": { "foreground": "#c586c0" } // Orange/Yellow for keywords
      },
      {
        "scope": "string",
        "settings": { "foreground": "#ce9178" } // Green for strings
      },
      {
        "scope": "variable",
        "settings": { "foreground": "#9cdcfe" } // Blue for variables
      },
      {
        "scope": "entity.name.tag",
        "settings": { "foreground": "#ccbf5f" } // Aqua for HTML tags
      },
      {
        "scope": "comment",
        "settings": { "foreground": "#6a9955", "fontStyle": "italic" } // Grey italicized comments
      },
      {
        "scope": "entity.name.function.js",
        "settings": {
          "foreground": "#3dc9b0" // Blue for all functions by default
        }
      },
      {
        "scope": "entity.other.attribute-name",
        "settings": {
          "foreground": "#c586c0"
        }
      }
    ]
  },
  "workbench.colorTheme": "Scrimba Dark Theme Editing"
}
