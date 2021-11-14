# Awesome server side languages

## Summary

- [About](#about)
- [Language comparison](#language-comparison)
- [Contribute](#contribute)

## About

I did not find any website or repository that provide a list of server side language to create web apps using back-end language. I thought of making one, to help developers to choose the language that fits their criteria.

## Language comparison

|                  |                                                [Node.js](https://nodejs.org/en/)                                                |                                  [PHP](https://www.php.net/)                                 |                               [Python](https://www.python.org/)                              |                                       [V](https://vlang.io/)                                      |
|------------------|:-----------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------:|:-----------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| Asynchronicity   | [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)       | no                                                                   | [yes](https://docs.python.org/3/library/asyncio-task.html)     | no                                                                           |
| Classes          |             [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Classes)             |        [yes](https://www.php.net/manual/en/language.oop5.php)        |       [yes](https://docs.python.org/3/tutorial/classes.html)      |                                      no                                      |
| Compiled         |                                                   no                                                  |                                  no                                  |                                 no                                |     [yes](https://github.com/vlang/v/blob/master/doc/docs.md#hello-world)    |
| Concurrency      | no                                                                                                    | no                                                                   | [yes](https://docs.python.org/3/library/threading.html)           | [yes](https://github.com/vlang/v/blob/master/doc/docs.md#concurrency)        |
| Constants        |         [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/const)        |        [yes](https://www.php.net/manual/en/function.constant.php)        |                                 no                                |      [yes](https://github.com/vlang/v/blob/master/doc/docs.md#constants)     |
|            Enums |                                                   no                                                  |             [yes](https://wiki.php.net/rfc/enumerations)             |         [yes](https://docs.python.org/3/library/enum.html)        |        [yes](https://github.com/vlang/v/blob/master/doc/docs.md#enums)       |
| Exceptions       |       [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)       |     [yes](https://www.php.net/manual/en/language.exceptions.php)     |    [yes](https://docs.python.org/3.10/tutorial/errors.html)    |                                      no                                      |
|         Generics |                                                   no                                                  |                                  no                                  |                                 no                                |      [yes](https://github.com/vlang/v/blob/master/doc/docs.md#generics)      |
| Immutability     |                                                   no                                                  |                                  no                                  |                                 no                                |      [yes](https://github.com/vlang/v/blob/master/doc/docs.md#variables)     |
| Interfaces       | no                                                                                                    | [yes](https://www.php.net/manual/en/language.oop5.interfaces.php)    | no                                                                | [yes](https://github.com/vlang/v/blob/master/doc/docs.md#interfaces)         |
| Interpreted      |                                                  yes                                                  |                                  yes                                 |                                yes                                |     [yes](https://github.com/vlang/v/blob/master/doc/docs.md#hello-world)    |
| Modules          | [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/import)               | no                                                                   | [yes](https://docs.python.org/3/tutorial/modules.html)            | [yes](https://github.com/vlang/v/blob/master/doc/docs.md#modules)            |
| Null             |       [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/null)       |     [yes](https://www.php.net/manual/en/language.types.null.php)     | [yes](https://docs.python.org/3.6/library/constants.html#None) |                                      no                                      |
| Package manager  | yes                                                                                                   | yes                                                                  | yes                                                               | [yes](https://github.com/vlang/v/blob/master/doc/docs.md#package-management) |
| Pattern matching |                                                   no                                                  |    [yes](https://wiki.php.net/rfc/enumerations#match_expressions)    |                                 no                                |        [yes](https://github.com/vlang/v/blob/master/doc/docs.md#match)       |
| Structs          | [yes](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Object_initializer) |                                  no                                  |     [yes](https://docs.python.org/3/library/dataclasses.html)     |       [yes](https://github.com/vlang/v/blob/master/doc/docs.md#structs)      |
| Type hints       | no                                                                                                    | [yes](https://www.php.net/manual/en/language.types.declarations.php) | [yes](https://docs.python.org/3/library/typing.html)              | [yes](https://github.com/vlang/v/blob/master/doc/docs.md#type-declarations)  |
| Union type       | no                                                                                                    | [yes](https://wiki.php.net/rfc/union_types_v2)                       | no                                                                | [yes](https://github.com/vlang/v/blob/master/doc/docs.md#sum-types)          |

## Contribute

1. Make sure your code editor support `.editorconfig` files
2. Make sure there is an issue before you create a pull request
3. Make sure to reference the number of the issue in your commits (for example, if you pull request is fixing the issue 56, the commit should be prefixed by `#56 fix typo on about section`)
4. Please prefix your message by "fix" or "add" (`#71 add C# language`, `#121 fix link for PHP doc on union types`)
5. Make sure to add a note (with a reference to the issue) on the "Unreleased" section of the changelog when you are ready to create a pull request

If you feel your contribution will involve a big rework, or you don't agree on the current state of this documentation, please create a discussion.

Thanks for contributing!
