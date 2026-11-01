# AstroView documentation

Read the [documentation site](https://chuuei.github.io/AstroView-docs/):

- [Core developer guide](https://chuuei.github.io/AstroView-docs/core/index.html)
- [Core API reference](https://chuuei.github.io/AstroView-docs/core/api/AstroView.Core.html)
- [Desktop user manual](https://chuuei.github.io/AstroView-docs/desktop/index.html)

This repository contains generated documentation and its Pages deployment
workflow. Application/library binaries and source files are maintained separately
in `Chuuei/AstroView`; access to that source repository may require permission.

Maintainers update the documentation from a successful `main` CI run using
`eng/Publish-Documentation.ps1 -RunId <run-id>` in the source repository. Generated
pages should be edited through their Markdown/XML-comment sources, then rebuilt
and validated by CI. `build-info.json` records the source commit and CI run.
