# demopkg

Mock terminal-interface package for the Sicht registry.

## Layout

- `demopkg.si` — the library (`demo_hello`, `demo_prompt`, `demo_menu`)
- `sicht.toml` — package manifest and dependencies

## Use

```
load library "demopkg"
take demo_menu from demopkg
print demo_menu(["a", "b"])
```
