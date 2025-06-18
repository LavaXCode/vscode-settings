# VS Code Settings

# Font

* [Anonymous Pro](https://www.marksimonson.com/fonts/view/anonymous-pro)

## Themes/Color

* [Dark Purple](https://marketplace.visualstudio.com/items?itemName=Makashi.dark-purple)
  * See [`editor.tokenColorCustomizations`](#settings) in my VS Code settings for a few modifications I make to the theme.

## Extensions

* Theme / Editor Experience
  * [FontSize ShortCuts](https://marketplace.visualstudio.com/items?itemName=fosshaas.fontsize-shortcuts)
    * Change the font size with keyboard shortcuts.
  * [vscode-icons](https://marketplace.visualstudio.com/items?itemName=vscode-icons-team.vscode-icons)
    * Nice / colorful icons for many different file types
  * [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
    * Automatically format javascript, JSON, CSS, Sass
  * [Paste JSON as Code](https://marketplace.visualstudio.com/items?itemName=quicktype.quicktype)
    * Auto generate TypeScript (and other languages) types from JSON data., and HTML files.
  * [Code Spell Checker](https://marketplace.visualstudio.com/items?itemName=streetsidesoftware.code-spell-checker)
    * Spell check markdown, comments and variable names.
  
* Useful Tools
  * [Code Snap](https://marketplace.visualstudio.com/items?itemName=adpyke.codesnap)
    * Take pictures of code with your VS Code Theme / Font settings.
* Languages and Libraries
  * [Tailwind CSS IntelliSense](https://marketplace.visualstudio.com/items?itemName=bradlc.vscode-tailwindcss)
    * Intelligent Tailwind CSS tooling for VS Code.
  * React
    * [ES7+ React/Redux/React-Native snippets](https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets)
      * Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax. Customizable. Built-in integration with prettier.
    * [CSS to JSS](https://marketplace.visualstudio.com/items?itemName=infarkt.css-to-jss)
      * Convert CSS to JSS
    * [CSS in JS](https://marketplace.visualstudio.com/items?itemName=paulmolluzzo.convert-css-in-js)
      * Get syntax highlighting when working with CSS in JS template strings.
    * [vscode-styled-components](https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components)
      * Syntax highlighting for styled-components.
  * [Prisma](https://marketplace.visualstudio.com/items?itemName=Prisma.prisma)
    * Adds syntax highlighting, formatting, auto-completion, jump-to-definition and linting for .prisma files.
  * [htmx-tags](https://marketplace.visualstudio.com/items?itemName=otovo-oss.htmx-tags)
    * Provides HTMX tag completion in HTML files in VSCode
  * [Markdown Mermaid Preview](https://marketplace.visualstudio.com/items?itemName=bierner.markdown-mermaid)
    * View Mermaid diagrams when previewing Markdown.

### Extension package names for easy install

```
Makashi.dark-purple
fosshaas.fontsize-shortcuts
vscode-icons-team.vscode-icons
esbenp.prettier-vscode
quicktype.quicktype
streetsidesoftware.code-spell-checker
yoavbls.pretty-ts-errors
quicktype.quicktype
adpyke.codesnap
bradlc.vscode-tailwindcss
dsznajder.es7-react-js-snippets
infarkt.css-to-jss
paulmolluzzo.convert-css-in-js
styled-components.vscode-styled-components
Prisma.prisma
otovo-oss.htmx-tags
bierner.markdown-mermaid
```

# Install in Single Commands
 * nano vs-extensions.txt
 * cat vs-extensions.txt | xargs -L1 code --install-extension
