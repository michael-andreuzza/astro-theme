# Astro Theme for VS Code.
Screenshots are coming soon...
This is my own version for Astro's VS Code theme
# Installation
1. Open **Extensions** sidebar panel in VS Code. `View → Extensions`
2. Search for **`Astro by Mike`** by Unwrapped
3. Click **Install** to install it.
4. Code > Preferences > Color Theme >
 **Astro by Mike**
## Personal Settings.
```js
{
  "editor.fontFamily": "'Dank Mono', monospace",
  "editor.fontSize": 18,
  "editor.lineHeight": 38,
  "editor.letterSpacing": 0.5,
  "files.trimTrailingWhitespace": true,
  "editor.fontWeight": "normal",
  "prettier.eslintIntegration": true,
  "editor.cursorStyle": "line",
  "editor.cursorWidth": 5,
  "editor.cursorBlinking": "phase",
  "editor.renderWhitespace": "all",
}
```
## Screenshots
Dark
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/astro.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/css.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/html.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/cpp.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/cs.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/java.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/js.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/md.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/py.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/dark/sh.png)
Light
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/astro.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/css.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/html.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/cpp.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/cs.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/java.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/js.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/md.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/py.png)
![VS Code Marketplace](https://raw.githubusercontent.com/michael-andreuzza/astro-theme/master/screenshots/light/sh.png)


The theme uses italics for certain language tokens by default.
To **disable** italics, add this snippet to your `settings.json`:
  - quotes and *italic* strings (like in markdown) will be unaffected and still be italic
  - if you want to exclude one of the themes from this change, simply remove its name (along with the brackets `[]`) at the top of the snippet
```jsonc
"editor.tokenColorCustomizations": {
  "[Astro by Mike]": {
    "textMateRules": [
      {
        "scope": [
          "comment",
          "variable",
          "variable.other.object.js",
          "variable.other.object.property",
          "variable.language",
          "punctuation.accessor",
          "markup.changed",
          "markup.deleted.diff",
          "markup.inserted.diff",
          "keyword",
          "keyword.operator.relational",
          "keyword.operator.comparison",
          "keyword.control.flow.js",
          "keyword.control.flow.ts",
          "keyword.control.flow.tsx",
          "keyword.control.ruby",
          "keyword.control.module.ruby",
          "keyword.control.class.ruby",
          "keyword.control.def.ruby",
          "keyword.control.loop.js",
          "keyword.control.loop.ts",
          "keyword.control.import.js",
          "keyword.control.import.ts",
          "keyword.control.import.tsx",
          "keyword.control.from.js",
          "keyword.control.from.ts",
          "keyword.control.from.tsx",
          "keyword.operator.instanceof.js",
          "keyword.operator.expression.instanceof.ts",
          "keyword.operator.expression.instanceof.tsx",
          "support.constant",
          "support.function",
          "entity.other.attribute-name",
          "entity.other.inherited-class",
          "entity.name.function",
          "entity.name.tag.doctype",
          "entity.name.function",
          "meta.directive.vue",
          "meta.diff.header.git",
          "meta.diff.header.from-file",
          "meta.diff.header.to-file",
          "meta.var.expr",
          "meta.delimiter.period",
          "meta.selector",
          "meta.tag.sgml.doctype",
          "meta.tag.sgml.doctype.html",
          "meta.class meta.method.declaration meta.var.expr storage.type.js",
          "storage",
          "storage.type.property.js",
          "storage.type.property.ts",
          "storage.type.property.tsx",
          "source.elixir .punctuation.binary.elixir",
          "source.go keyword.package.go",
          "source.go keyword.import.go",
          "source.go keyword.function.go",
          "source.go keyword.type.go",
          "source.go keyword.struct.go",
          "source.go keyword.interface.go",
          "source.go keyword.const.go",
          "source.go keyword.var.go",
          "source.go keyword.map.go",
          "source.go keyword.channel.go",
          "source.go keyword.control.go",
          "string.quoted.docstring.multi.python",
        ],
        "settings": {
          "fontStyle": ""
        },
      },
    ],
  },
},
```
I am not affiliated with Astro team, nor is it endorsed by or sponsored by this one. A side project by Michael Andreuzza and is crafted in Åland Islands, Finland.
*Astro Theme* Theme created by [Micheal Andreuzza](https://github.com/michael-andreuzza).
[Twitter](https://twitter.com/Mike_Andreuzza)
# Astro Dark
# astro-theme
