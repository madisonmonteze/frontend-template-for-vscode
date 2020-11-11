## VS Code setup for Frontend Workflow

HTML + SASS + JS setup template for web development. Use with VS Code 'Live Sass Compiler' and 'Live Server' plugins.

Based on this setup from Coder Coder: [link](https://www.youtube.com/watch?v=aydFCQiUW44). 

Added Live Sass setting in VS Code settings.json:
```json
"liveSassCompile.settings.formats": [
        {
            "format": "compressed",
            "extensionName": ".css",
            "savePath": "/dist"
        }
    ]
```
