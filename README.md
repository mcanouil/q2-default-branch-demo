# q2 default branch demo

This repository is a test fixture for [quarto-dev/q2](https://github.com/quarto-dev/q2).
It holds a small Quarto extension, `demo`, which does nothing to the document.

The default branch is `develop`, and the repository also has an older `main` branch:

| Branch | Role | Extension version |
| --- | --- | --- |
| `develop` | Default branch. | 2.0.0 |
| `main` | Older branch, kept on purpose. | 1.0.0 |

A tool that installs `mcanouil/q2-default-branch-demo` with no `@ref` should get version 2.0.0 from `develop`.
If it gets version 1.0.0, it took `main` instead of the default branch.

Don't use this extension in a real project.
