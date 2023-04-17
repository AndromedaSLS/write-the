# 🤖 write-the

AI-powered Documentation and Test Generation Tool

[![PyPI - Version](https://img.shields.io/pypi/v/write-the.svg)](https://pypi.org/project/write-the)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/write-the.svg)](https://pypi.org/project/write-the)
[![write-the - docs](https://badgen.net/badge/write-the/docs/blue?icon=https://raw.githubusercontent.com/Wytamma/write-the/master/images/write-the-icon.svg)](https://write-the.wytamma.com/)
[![write-the - docs](https://badgen.net/badge/write-the/tests/green?icon=https://raw.githubusercontent.com/Wytamma/write-the/master/images/write-the-icon.svg)](https://write-the.wytamma.com/)


Write-the is an AI-powered documentation and test generation tool that leverages GPTs to automatically write tests, generate documentation, and refactor code. It is designed to streamline the development process, improve code quality, and increase productivity.

![](https://raw.githubusercontent.com/Wytamma/write-the/master/images/multiply.png)

-----

**Table of Contents**

- [Features](#Features)
- [Requirements](#Requirements)
- [Installation](#Installation)
- [Usage](#Usage)
- [Roadmap](#Roadmap)
- [Contributing](#Contributing)
- [License](#License)


## Installation
```console
pip install write-the
```
## Features

Write-the offers the following AI-driven features:
- Write-the Docs: Automatically generate documentation for your codebase, including class and function descriptions, parameter explanations, and examples.
- Write-the Tests: Create test cases for your code, ensuring thorough test coverage and better code quality (TBD).
- Write-the Refactor: Receive refactoring suggestions, reduce code complexity, optimize performance, and fix bugs (TBD).

## Requirements
- Python 3.9 or higher  
- OpenAI API key

## Usage
To use `write-the`, run the following commands:

### Docs:
```bash
write-the docs [OPTIONS] [PATH_TO_SOURCE_CODE]
```

![](https://raw.githubusercontent.com/Wytamma/write-the/master/images/docs-help.png)

Real-world examples:
- [`write-the docs` to write the docs for the `write-the docs` command 🤖](https://github.com/Wytamma/write-the/blob/master/write_the/docs/write.py#L14)

### Mkdocs:
```bash
write-the mkdocs [OPTIONS] [PATH_TO_SOURCE_CODE]
```

![](https://raw.githubusercontent.com/Wytamma/write-the/master/images/mkdocs-help.png)

Real-world examples:
- [`write-the docs` and `write-the mkdocs` to build documenation for `autoresearcher` 🤖](https://github.com/eimenhmdt/autoresearcher/pull/17)

For detailed information on available options and parameters, refer to the official (`write-the` generated) [documentation](https://write-the.wytamma.com/).

## Roadmap

For a detailed project roadmap, including planned features, improvements, and milestones, please see our Project Timeline.

## Contributing
We welcome contributions from the community. If you would like to contribute to Write-The, please follow these steps:

- Fork the repository and create a new branch for your feature or bugfix.
- Develop your changes and ensure that your code follows the project's coding standards.
- Create a pull request with a clear description of your changes and any relevant documentation.
- For more information on contributing, please see our Contributing Guide.

## License
`write-the` is distributed under the terms of the [MIT](https://spdx.org/licenses/MIT.html) license.

