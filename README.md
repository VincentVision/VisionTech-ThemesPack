# Pack de thèmes Vision Tech Gyver

Vous trouverez dans ce pack les thèmes VS Code par [Vincent Vision](https://www.youtube.com/channel/UC0obaoAHO-BMgIXGjGoZHOA). Retrouvez également le pack d'extensions VisionTech ExtensionPack pour un VS Code plus Smart.

## High Contrast (VisionTech)


# Configurations

Vous pouvez également utiliser les configurations de VS Code des [vidéos](https://www.youtube.com/channel/UC0obaoAHO-BMgIXGjGoZHOA) :
- Télécharger et installer la police [Fira Code iScript](https://github.com/kencrocken/FiraCodeiScript) sur votre ordinateur.
- Sur VS Code faites la combinaison de toûches suivante. `Ctrl + Maj + P`
- Puis recherchez "open settings" et cliquez sur "Open Settings (JSON)".
- Enfin remplacer le contenu du fichier "settings.json" par le suivant sans oublier de sauvegarder.

```json
{
    "window.zoomLevel": 1,
    "explorer.compactFolders": false,
    "bracket-pair-colorizer-2.colors": [
      "Gold",
      "#018001",
      "#3769fe"
    ],
    "better-comments.tags": [
      {
        "tag": "!",
        "color": "#FF2D00",
        "strikethrough": false,
        "underline": true,
        "backgroundColor": "transparent",
        "bold": false,
        "italic": true
      },
      {
        "tag": "?",
        "color": "#3769fe",
        "strikethrough": false,
        "underline": false,
        "backgroundColor": "transparent",
        "bold": true,
        "italic": false
      },
      {
        "tag": "*",
        "color": "#018001",
        "strikethrough": false,
        "underline": false,
        "backgroundColor": "transparent",
        "bold": false,
        "italic": false
      }
    ],
    "vsintellicode.modify.editor.suggestSelection": "automaticallyOverrodeDefaultValue",
    "[javascript]": {
      "editor.defaultFormatter": "vscode.typescript-language-features"
    },
    "git.enableSmartCommit": true,
    "git.autofetch": true,
    "[json]": {
      "editor.defaultFormatter": "vscode.json-language-features"
    },
    "editor.renderIndentGuides": false,
    "editor.wordWrap": "on",
    "workbench.colorTheme": "High Contrast (VisionTech)",
    "editor.tabSize": 2,
    "editor.fontFamily": "Fira Code iScript",
    "editor.fontLigatures":true,
"editor.tokenColorCustomizations": {
  "textMateRules": [
    {
      "scope": [
        //following will be in italic
        "comment",
        "entity.name.type.class", //class names
        "keyword", //import, export, return…
        "constant", //String, Number, Boolean…, this, super
        "storage.modifier", //static keyword
        "storage.type.class.js", //class keyword
      ],
      "settings": {
      "fontStyle": "italic"
      }
    },
    {
      "scope": [
        //following will be excluded from italics (VSCode has some defaults for italics)
        "invalid",
        "keyword.operator",
        "constant.numeric.css",
        "keyword.other.unit.px.css",
        "constant.numeric.decimal.js",
        "constant.numeric.json"
      ],
      "settings": {
      "fontStyle": ""
      }
    }
  ]
},
"editor.cursorStyle": "line",
"editor.cursorWidth": 6,
"editor.cursorBlinking": "expand",
"editor.multiCursorModifier": "ctrlCmd",
"editor.mouseWheelZoom": true,
"editor.tabCompletion": "on",
"editor.formatOnPaste": true,
"editor.minimap.size": "fit",
"editor.acceptSuggestionOnEnter": "off",
"editor.suggest.showStructs": false,
"workbench.quickOpen.preserveInput": true,
"workbench.preferredDarkColorTheme": "Dark+++ (VisionTech)",
"workbench.preferredHighContrastColorTheme": "High Contrast (VisionTech)",
"breadcrumbs.enabled": false,
"window.dialogStyle": "custom",
"window.titleSeparator": "◡◠◡◠",
"explorer.confirmDragAndDrop": false,
"extensions.closeExtensionDetailsOnViewChange": true,
"extensions.ignoreRecommendations": true,
"javascript.format.insertSpaceAfterConstructor": true,
"javascript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
"javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
"javascript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
"javascript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
"javascript.format.insertSpaceBeforeFunctionParenthesis": true,
"javascript.format.placeOpenBraceOnNewLineForControlBlocks": true,
"javascript.format.placeOpenBraceOnNewLineForFunctions": true,
"typescript.format.insertSpaceAfterConstructor": true,
"typescript.format.insertSpaceAfterOpeningAndBeforeClosingJsxExpressionBraces": true,
"typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyBrackets": true,
"typescript.format.insertSpaceAfterOpeningAndBeforeClosingNonemptyParenthesis": true,
"typescript.format.insertSpaceAfterOpeningAndBeforeClosingTemplateStringBraces": true,
"typescript.format.insertSpaceBeforeFunctionParenthesis": true,
"typescript.format.placeOpenBraceOnNewLineForControlBlocks": true,
"typescript.format.placeOpenBraceOnNewLineForFunctions": true,
"typescript.format.semicolons": "insert",
"editor.autoIndent": "advanced",
"editor.smoothScrolling": true,
"editor.suggestSelection": "first"
}
```

# License

[VVS](https://github.com/VincentVision/VisionTech-ExtensionPacks/blob/main/LICENSE)