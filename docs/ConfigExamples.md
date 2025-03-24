# Configuration Examples

#### `.clang-format`

```yaml
---
Language: Cpp
ColumnLimit: 100
IndentWidth: 2
```

#### `.gitignore`

```
**/.**
**/__pycache__
**/data
**/__pycache__
**/*.model
*.zip
*.pyc
*.pyo
```

#### `.vscode/launch.json`

```json
{
  "version": "0.2.0",
  "configurations": [
    {
      "name": "debug main.py",
      "type": "debugpy",
      "request": "launch",
      "program": "${workspaceRoot}/main.py",
      "console": "integratedTerminal",
      "args": ["--test_case", "./tests/case2.json"]
    }
  ]
}
```

#### `VSCode settings.json`

```json
{
  "http.proxy": "http://1.2.3.4:1234",

  // window
  "window.commandCenter": false,
  // workbench
  "workbench.editor.empty.hint": "hidden",
  "workbench.layoutControl.enabled": false,
  "workbench.activityBar.location": "top",
  "workbench.secondarySideBar.showLabels": false,
  // editor
  "editor.minimap.enabled": false,

  // langguage settings
  "[markdown]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[jsonc]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[yaml]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  // python
  "[python]": {
    "editor.defaultFormatter": "charliermarsh.ruff"
  },
  "ruff.lineLength": 100,
}
```