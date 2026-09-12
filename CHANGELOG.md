# Change Log

## [0.0.3] - 2026-09-12

### Added
- Rocker comment highlighting for `@* ... *@` blocks (single- and multi-line), in both template body and HTML attribute contexts

## [0.0.2] - 2026-05-25

### Added
- Before/after preview screenshots in README

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
