# LaTeX Mathematics Commands

## Philosophy

When you write mathematics in LaTeX, you should write the content and meaning of the mathematics.
The styling information should be listed in a separate file, in this case, a packages by yours truly.

For example, `$x \in \mathbb{C}$` should be replaced by `$x \in \ComplexNumbers$`, and the styling for `\ComplexNumbers` is defined in the package.

The advantages are as follows.

1. This makes the LaTeX file more readable.
2. This allows you to change conventions by overriding the package, so one could write
    ``` latex
    \renewcommand{\ComplexNumbers}{\mathbf{C}}
    ```
    in your LaTeX file to change to a boldface 'C'.

## Contents

This repository contains the following packages.

* `math-commands-generic`: numbers, linear algebra

## Conventions

* The commands that the package defines must be in CamelCase.

## Repository Information

This repository is still in development, and there are many definitions to be added to the project.

### Maintainer

This repository is maintained by [Todd Liebenschutz-Jones](https://www.toddljones.me) ([email](mailto:dev@toddljones.me)).

### License

This repository is licensed by a [MIT License](https://opensource.org/licenses/MIT).
See [LICENSE.txt](https://github.com/toddlj/latex-math-commands/blob/master/LICENSE.txt) for full terms.
