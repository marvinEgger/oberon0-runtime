# Runtime for Oberon-0
This repository contains a *runtime* for the Oberon-o language. A runtime is a execution envionment allowing the execution of compiles code in a specific language. In this project a runtime in Python for executing compiled `WASM` code.

## How to use

**Run the program**

```bash
oberon0-rt run add.wasm add 23 19
```

**generate documentation**
```bash
uv run .\make.bat html
```

**bump up the verion**

patch (0.1.0 -> 0.1.1)
```bash
uv run bump-my-version bump patch
```

minor (0.1.1 -> 0.2.0)
```bash
uv run bump-my-version bump minor
```

major (0.1.2 -> 2.0.0)
```bash
uv run bump-my-version bump minor
```