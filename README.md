# cookiecutter-uv-example

[![Release](https://img.shields.io/github/v/release/fpgmaas/cookiecutter-uv-example)](https://img.shields.io/github/v/release/fpgmaas/cookiecutter-uv-example)
[![Build status](https://img.shields.io/github/actions/workflow/status/fpgmaas/cookiecutter-uv-example/main.yml?branch=main)](https://github.com/fpgmaas/cookiecutter-uv-example/actions/workflows/main.yml?query=branch%3Amain)
[![codecov](https://codecov.io/gh/fpgmaas/cookiecutter-uv-example/branch/main/graph/badge.svg)](https://codecov.io/gh/fpgmaas/cookiecutter-uv-example)
[![Commit activity](https://img.shields.io/github/commit-activity/m/fpgmaas/cookiecutter-uv-example)](https://img.shields.io/github/commit-activity/m/fpgmaas/cookiecutter-uv-example)
[![License](https://img.shields.io/github/license/fpgmaas/cookiecutter-uv-example)](https://img.shields.io/github/license/fpgmaas/cookiecutter-uv-example)

This is a template repository for Python projects that use uv for their dependency management.

- **Github repository**: <https://github.com/fpgmaas/cookiecutter-uv-example/>
- **Documentation** <https://fpgmaas.github.io/cookiecutter-uv-example/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

```bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:fpgmaas/cookiecutter-uv-example.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with

```bash
make install
```

You are now ready to start development on your project!
The CI/CD pipeline will be triggered when you open a pull request, merge to main, or when you create a new release.

To finalize the set-up for publishing to PyPi or Artifactory, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/publishing/#set-up-for-pypi).
For activating the automatic documentation with MkDocs, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/mkdocs/#enabling-the-documentation-on-github).
To enable the code coverage reports, see [here](https://fpgmaas.github.io/cookiecutter-uv/features/codecov/).

## Releasing a new version

---

Repository initiated with [fpgmaas/cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv).
