# Rocker Template Syntax Highlight

Syntax highlighting for [Rocker](https://github.com/fizzed/rocker) `.rocker.html` template files — a Java-based, statically typed templating engine.

## Features

- **Control flow** — `@if`, `@else if`, `@else`, `@for`, `@while`, `@with` highlighted as keywords
- **Expressions** — `@variable`, `@object.method()`, `@Class.staticMethod()` with dot-chain coloring
- **Template calls** — `@Template.template(args)` with full argument highlighting
- **Declarations** — `@args` type signatures with generic support (`Map<String, Object>`)
- **Imports** — `@import` statements
- **Java literals** — strings, numbers, `true` / `false` / `null`, primitive types
- **Operators** — `!=`, `==`, `&&`, `||`, `++`, `--`, `+`, and comparison operators
- **Block delimiters** — `{` and `}` visually distinct from surrounding HTML
- **Injection grammar** — Rocker expressions inside HTML attribute values are highlighted correctly, including deeply nested calls like `@Util.method(map.get("key"+"suffix"))`
- **Light & dark theme support** — color rules adapt to both light and dark VS Code themes

## Requirements

No additional dependencies. The extension activates automatically for files matching `*.rocker.html`.

## Known Issues

- **Comparison operator color** — The less-than and greater-than operators used inside `@if` / `@for` conditions may render with a theme-dependent color in some edge cases instead of the standard operator color. This is a TextMate grammar priority conflict between the Rocker grammar and the base HTML grammar. Compound operators such as `!=`, `==`, `&&`, and `||` are not affected.

## Release Notes

### 0.0.1

Initial release — full syntax highlighting for Rocker template files.
