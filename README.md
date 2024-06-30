# Protos Coding Language
Protos is a language designed to unite all existing languages into one while keeping as much readability as possible. Elements from languages such as Python, JavaScript, Lua, and C/C#/C++ are all a part of the language.

# The Concept
Protos is a heavily functional language. So much so that minor changes can completely change the behaviour of a function. Small differences can have large impacts, and it is all for the purpose of simply being able to add all of the promised functionality.

## The Syntax:
Protos' syntax is designed to be predictable, and is meant to unify syntaxes from many different languages, adding a less steep learning curve for the language

### Variable Definition:
Variables have a long and drawn out declaration condtruct, though it does make sense once explained.
```
standard new variable:var() ; string() "Greeting" = "Hello World!"
```
Seems complex, right? Well let's break it down:
- `standard` is the protocol definer. It follows the same functionality as `public` or `private`.
- `new` is a basic independent keyword for new data.
- `variable` works in partnership with `new`. It identifies what `new` is referring to.
- `:` in this instance is being used as property **retrieval** (not property assignment).
- `var()` is what you would see in other languages. Just a basic variable, but it can also accept arguments.
- `;` is being used as type assignment, though in general a semicolon denotes property unification:
  - Under normal circumstances, a `:` would be just fine, as `variable` does have a `string()` property. However, a `:` only affects the leftmost data (which would be `var()`, which does not have a `string()` property). Therefore, it is not applicable
- `string()` is a basic data type, and it supports arguments (mainly for text encoding and such).
- `"Greeting"` is obviously the actual name of the variable. It is surrounded by quotation marks for more explicit definition and readability purposes.
- The `=` has not changed function.
- `"Hello World!` is the assigned data, nothing new there.
