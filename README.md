# LaTeX Mathematics Commands

## Philosophy

When you write mathematics in LaTeX, you should write the content and meaning of the mathematics.
The styling information should be listed in a separate file, in this case, a package by yours truly.

For example, `$x \in \mathbb{C}$` should be replaced by `$x \in \ComplexNumbers$`, and the styling for `\ComplexNumbers` is defined in the package.

The advantages are as follows.

1. This makes the LaTeX file more readable.
2. This allows you to change conventions by overriding the package, so one could write `$\newcommand{\ComplexNumbers}{\mathbf{C}}` in your LaTeX file to change to a boldface 'C'.

## Conventions

The commands that the package defines must be in CamelCase.
