## 2.2.0 - unreleased

ADDED:

CHANGED:

REMOVED:

FIXED:

## 2.1.0 - 2019-10-04

CHANGED:

- Require PHP CodeSniffer 3.5.0 at least

## 2.0.1 - 2019-08-22

REMOVED:

- Check to forbid usage of conditions when a simple return can be used
- Check to require types to be written as natively if possible
- Check to force rules for function phpDoc

## 2.0.0 - 2019-08-22

ADDED:

- Check to forbid duplicate class names
- Check to forbid inline HTML in PHP code
- Check to forbid alias functions
- Check to forbid Late Static Binding of constants
- Check to forbid dead code
- Check to specific order of phpDoc annotations with empty newline between groups
- Check to forbid useless comments
- Check to require comments with single line written as one-liners
- Check to forbid assignments in conditions
- Check to require consistent spacing for control structures
- Check to forbid usage of conditions when a simple return can be used
- Check to forbid usage of boolean-only ternary operator usage
- Check to forbid useless unreachable catch blocks
- Check to require closures not referencing $this be static
- Check to require newlines around namespace declaration
- Check to require only one namespace declaration in a file
- Check to forbid useless alias for classes, constants and functions
- Check to require no spacing after spread operator
- Check to forbid argument unpacking for functions specialized by PHP VM
- Check to forbid useless semicolon
- Check to require types to be written as natively if possible
- Check to forbid useless @var for constants
- Check to forbid duplicated variables assignments
- Check to forbid useless variables
- Check to force rules for function phpDoc
- Check to forbid global functions
- Check to forbid functions inside functions
- Check to forbid superfluous whitespaces

CHANGED:

- Increased minimum PHP version requirement to 7.4

## 1.1.2 - 2019-02-07

REMOVED:

- Check for early exit

## 1.1.1 - 2019-02-07

FIXED:

- `DisallowEqualOperatorsSniff` was moved to another namespace

## 1.1.0 - 2019-02-07

ADDED:

- Check for spread operator spacing
- Check for useless else/elseif conditions

## 1.0.0 - 2018-12-21

- Initial release
