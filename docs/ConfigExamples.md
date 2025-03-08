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
