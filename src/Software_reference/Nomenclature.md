# 🏷️ Nomenclature

Here you will find the nomenclature and casing conventions used in Xila.
I know, it doesn't follow the [Rust naming conventions](https://doc.rust-lang.org/1.0.0/style/style/naming/README.html) but it my own convention and I like it.

## General rules

For all the identifiers:
- All the names are in English.
- Each identifier starts with a capital letter and is then camel cased (e.g. `This_is_an_identifier`).
- Each words are separated by an underscore `_`.
- No abbreviation.

## Types

All types should end with `_type` suffix.

## Functions

For functions, use the following rules:
- Constructor : starts with `New`. 
- Accessor : starts with `Get` or `Set`.
- Callback : ends with `_callback` suffix.
- Others : starts with a **verb** corresponding to the main action it performs.

## Comments

For comments, use the following rules:
- Use `//` for single line and multi-line comments (no `/* */`).
- If the comment concerns a block of code, add `-` corresponding to the scope level of the comment.