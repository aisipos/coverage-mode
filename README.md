# Code coverage highlighting for Emacs

A fork of [fork][fork] with Python coverage support.

## Usage

To enable `code-coverage` in the current buffer, use `M-x
code-coverage RET`. Repeat this command to disable.

## Configuration

By default, `code-coverage` looks in your current `vc-git-root`
directory for the `coverage/.resultset.json` file. You can configure
this to whatever filepath you want through the `Coverage Dir`
customization variable.

You can also choose your own `faces` for covered & uncovered lines
through customization variables. These default to green for covered &
red for uncovered.

[fork]: https://github.com/trezona-lecomte/coverage-mode
