# Change Log

## [0.0.1] - 2026-05-24

### Added
- Syntax highlighting for Rocker `.rocker.html` template files
- Control flow keywords: `@if`, `@else if`, `@else`, `@for`, `@while`, `@with`
- Expression highlighting with dot-chain support: `@obj.method().field`
- Template call highlighting: `@Template.template(args)`
- `@args` type declarations with Java generics support
- `@import` statement highlighting
- Java literals: strings, numbers, booleans, `null`, primitive types
- Operator highlighting: `!=`, `==`, `<=`, `>=`, `&&`, `||`, `++`, `--`, `+`, `-`
- Injection grammar for Rocker expressions inside HTML attribute values
- Light and dark theme color support via `[*Dark*]` / `[*Light*]` token rules
