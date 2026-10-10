# Character

Defined in character@1.0.1

This module provides wrapper functions of C functions defined in ctypes.h.

Each function takes a character as a byte (`U8`), such as the character literal `'a'`.

```fix
assert(|_|"", is_digit('7'));;
assert(|_|"", !is_alpha('7'));;
assert_eq(|_|"", to_upper('a'), 'A')
```

## Values

### namespace Character

#### is_alnum

Type: `Std::U8 -> Std::Bool`

#### is_alpha

Type: `Std::U8 -> Std::Bool`

#### is_blank

Type: `Std::U8 -> Std::Bool`

#### is_cntrl

Type: `Std::U8 -> Std::Bool`

#### is_digit

Type: `Std::U8 -> Std::Bool`

#### is_graph

Type: `Std::U8 -> Std::Bool`

#### is_lower

Type: `Std::U8 -> Std::Bool`

#### is_print

Type: `Std::U8 -> Std::Bool`

#### is_punct

Type: `Std::U8 -> Std::Bool`

#### is_space

Type: `Std::U8 -> Std::Bool`

#### is_upper

Type: `Std::U8 -> Std::Bool`

#### is_xdigit

Type: `Std::U8 -> Std::Bool`

#### to_lower

Type: `Std::U8 -> Std::U8`

#### to_upper

Type: `Std::U8 -> Std::U8`

## Types and aliases

## Traits and aliases

## Trait implementations