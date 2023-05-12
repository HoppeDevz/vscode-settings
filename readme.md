## My VS Code Settings

All extensions:
```
    Name: background
    Id: shalldie.background
    Description: Bring background images to your vscode
    Version: 1.2.9
    Publisher: shalldie
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=shalldie.background
    
    Name: Bracket Pair Color DLW
    Id: BracketPairColorDLW.bracket-pair-color-dlw
    Description: Quickly 'Bracket Pair Color DLW' setting with a simple command
    Version: 0.0.6
    Publisher: Bracket Pair Color DLW
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=BracketPairColorDLW.bracket-pair-color-dlw

    Name: C/C++
    Id: ms-vscode.cpptools
    Description: C/C++ IntelliSense, debugging, and code browsing.
    Version: 1.15.4
    Publisher: Microsoft
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode.cpptools

    Name: Color Highlight
    Id: naumovs.color-highlight
    Description: Highlight web colors in your editor
    Version: 2.5.0
    Publisher: Sergii N
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=naumovs.color-highlight

    Name: Error Lens
    Id: usernamehw.errorlens
    Description: Improve highlighting of errors, warnings and other language diagnostics.
    Version: 3.11.0
    Publisher: Alexander
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=usernamehw.errorlens

    Name: ESLint
    Id: dbaeumer.vscode-eslint
    Description: Integrates ESLint JavaScript into VS Code.
    Version: 2.4.0
    Publisher: Microsoft
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint

    Name: GitLens — Git supercharged
    Id: eamodio.gitlens
    Description: Supercharge Git within VS Code — Visualize code authorship at a glance via Git blame annotations and CodeLens, seamlessly navigate and explore Git repositories, gain valuable insights via rich visualizations and powerful comparison commands, and so much more
    Version: 13.6.0
    Publisher: GitKraken
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens

    Name: JavaScript and TypeScript Nightly
    Id: ms-vscode.vscode-typescript-next
    Description: Enables typescript@next to power VS Code's built-in JavaScript and TypeScript support
    Version: 5.1.20230511
    Publisher: Microsoft
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=ms-vscode.vscode-typescript-next

    Name: Material Icon Theme
    Id: PKief.material-icon-theme
    Description: Material Design Icons for Visual Studio Code
    Version: 4.27.0
    Publisher: Philipp Kief
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme

    Name: Material Theme Icons
    Id: equinusocio.vsc-material-theme-icons
    Description: Material Theme Icons, the most epic icons theme for Visual Studio Code and Material Theme.
    Version: 2.7.5
    Publisher: Equinusocio
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=Equinusocio.vsc-material-theme-icons

    Name: SQL Lit
    Id: thebearingedge.vscode-sql-lit
    Description: Syntax highlighting for SQL tagged template literals in JavaScript and TypeScript.
    Version: 0.6.1
    Publisher: thebearingedge
    VS Marketplace Link: https://marketplace.visualstudio.com/items?itemName=thebearingedge.vscode-sql-lit
```


Settings.json
```json
{
    "workbench.iconTheme": "material-icon-theme",

    "explorer.compactFolders": false,

    "editor.smoothScrolling": true,
    "editor.cursorSmoothCaretAnimation": "on",

    "editor.fontFamily": "Fira Code, Consolas, 'Courier New', monospace",
    "editor.fontLigatures": true,

    "background.fullscreen": {
        "image": "https://i.imgur.com/b04frWQ.png", // url of your image
        // "image": ["https://pathtoimage.png"], // An array may be useful when set interval for carousel
        "opacity": 0.95, // 0.85 ~ 0.95 recommended
        "size": "cover", // also css, `cover` to self-adaption (recommended)，or `contain`、`200px 200px`
        "position": "center", // alias to `background-position`, default `center`
        "interval": 0 // seconds of interval for carousel, default `0` to disabled.
    },
    "workbench.colorTheme": "Monokai Theme",
    "window.zoomLevel": -1
    
}
```