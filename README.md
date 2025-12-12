<h1 align="center">
  BARBIE CYBERPUNK Theme
</h1>

<p align="center">
  <a href="https://marketplace.visualstudio.com/items?itemName=your-publisher-name.barbie-cyberpunk">
    <img src="https://img.shields.io/visual-studio-marketplace/v/your-publisher-name.barbie-cyberpunk?style=popout-square" alt="Marketplace version" />
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=your-publisher-name.barbie-cyberpunk#review-details">
    <img src="https://img.shields.io/visual-studio-marketplace/stars/your-publisher-name.barbie-cyberpunk?style=popout-square" alt="Rating" />
  </a>
</p>

<p align="center">
  A vibrant dark VS Code theme with neon pink, cyan, and yellow syntax highlighting inspired by Barbie cyberpunk aesthetics.
</p>

## Preview

<p align="center">
  <img src="https://github.com/SENERYTY-DEV/barbie-cyberpunk/blob/main/screenshots/wallper1.png?raw=true" alt="BARBIE CYBERPUNK preview" style="max-width:100%;height:auto;" />
</p>


## Installation

Install from the VS Code Marketplace or use the generated `.vsix`:

```bash
# copy screenshots (optional)
node ./scripts/copy-screenshots.js
# package
npx vsce package
# install resulting vsix
code --install-extension barbie-cyberpunk-*.vsix
