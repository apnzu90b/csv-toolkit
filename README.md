# csv-toolkit

Small CLI utilities for slicing, filtering and joining CSV files.

## Why

I kept rewriting the same thirty lines in every project, so I pulled them out.

## Install

```bash
pip install csv-toolkit
```

## Usage

```python
from csv_toolkit import csvToolkit

result = csvToolkit("example")
print(result)
```

## Notes

- No runtime dependencies outside the standard library.
- Tested on Python 3.9 and newer.

## License

MIT
