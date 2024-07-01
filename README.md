# Protos Coding Language
Protos (A.K.A ProtoCode) is a language which has the functionality of low level, mid level, and high level languages, while keeping a generally understandable syntax. It amalgamates writing methods from already popular languages such as Python, JavaScript, Lua, C/C#/C++ while adding its own unique aspects.

Protos is an incredibly diverse language, offering great functionality in any situation, while keeping a mostly predictable synatax to make it as new-user friendly as possible.

## Why?
Ever since the idea of programming languages began, there have been countless languages all with their own purposes and use-cases. That is good, but the problem stems from the fact that each language has its own syntax, which makes working with multiple languages extremely difficult. Protos aims to solve the langauge barrier and create a universal programming language which anybody can learn and use without the fear of requiring to switch to a completely new language.

## Syntax
Protos' syntax is designed to be predictable, yet functional. You should be able to envision how to structure whatever you'd like to make, and be able to execute that idea with minimal issues. If you ever do go wrong, Protos will not leave you in the dark, errors are designed to be informative as well as *corrective*, preventing you from scratching your head in confusion.

However, Protos still uses its own syntax type. Yes, this does mean you will need to learn Protos, but when you do learn Protos, it almost completely eliminates the need to learn any other language. It may not be the most intuitive of languages, but it definitely gets the correct job done without issue.

In general, Protos uses a logical syntax structure, as well as constructs. However, it is easy to discern whether to use a lixend (function) versus a construct (multiple independent keywords).

## How does it work?
Protos has an extremely complex way of functioning, though it is for the better:
In general, the version of Protos most use is the base version, which features the promised aspects. However, the base version runs on a source version, which acts as a sort of assembly language for itself. The amount of processes that Protos uses are vast, and simply cannot be done on the front end, meaning there has to be a back end. This is also why Protos *would* only work on its own IDEs, because Protos-B (Protos Base) relies on Protos-S (Protos Source).
And there's no denying it - Protos is not memory efficient. The sheer amount of functionality bars any memory or speed efficiency. In that case, how do you use Protos to create games? The answer is you do it as you normally would. Despite the performance hits, the actual difference is minimal.

## How does it look?
Now, let's give you an idea of how Protos is structured an written so that the base knowledge is there.
### Variables:
  Variables in Protos have quite a verbose way of being defined:
  ```
standard new variable:var() ; string() "Greeting" = "Hello World!"
  ```
  As you can see, there are a lot of points to cover:
  - Firstly, the keyword `standard` acts as the protocol definer. This specifies what permission level the traffic sender requires (this is similar to `public` and `private`).
  - Secondly, the keyword `new` is what initiates a creation format. By removing `standard`, it is more easy to see that `new` in Protos acts in place of `var` or `const`
  - Thirdly, what we are defining. In this example, we are using `variable` to identify a ***new** variable*.
  - Fourth, the colon. In this function context, the colon acts as property **retrieval** (not assignment).
  - In conjunction with the colon, we then use `var()` to signify the variable's behaviour (is it constant, limited scope? etc...).
  - The semicolon is for type assignment (not universally). Normally, a colon could be used but the colon only assigns the right value to the closest left value, but `var()` cannot have a property of `string()`, only `variable` can. Therefore, we use the semicolon to signify that we are still assigning something, but not from `var()` directly.
  - `string()` is a basic data type.
  - `"Greeting"` is the actual name of the variable. It is surrounded in quotes for both readability and sectioning.
  - `=` has not changed function.
  - `"Hello World!"` is the assigned value.
  This is quite a *complex* way of defining a simply variable, though it is for all intents and purposes to be worth a thousand words. You can see what permission level, variable type, and data type the variable is. The name is also easility locatable as most codespaces assign a unique colour to strings.
