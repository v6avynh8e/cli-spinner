# cli-spinner

Spinners and progress bars that degrade gracefully when not a TTY.

## Why

The existing libraries were either abandoned or pulled in a large dependency tree.

## Install

```bash
pip install cli-spinner
```

## Usage

```python
from cli_spinner import cliSpinner

result = cliSpinner("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
