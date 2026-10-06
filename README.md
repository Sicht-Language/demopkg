# demopkg

Mock terminal-interface package for the Sicht registry.

## Layout

- `demopkg/package.si` — the library (`demo_hello`, `demo_prompt`, `demo_menu`)
- `demopkg/terminal.si` — terminal helpers used by the library
- `tests/` — usage checks for the package
- `sicht.toml` — package manifest and dependencies

## Use

```
load library "demopkg"
take demo_menu from demopkg
print demo_menu(["a", "b"])
```
