# Markdown Lint Configuration

[![Build Status](https://travis-ci.org/strictr/markdown-lint-config.svg?branch=master)](https://travis-ci.org/strictr/markdown-lint-config)

[![npm version](https://badge.fury.io/js/%40strictr%2Fmarkdown-lint-config.svg)](https://badge.fury.io/js/%40strictr%2Fmarkdown-lint-config)

A portable markdown lint configuration.

## Installation

In order to use this configuration in your project you can run the following command:

```bash
npm i @strictr/markdown-lint-config -D
```

And after that in your `.markdownlint.json` can look like this:

```json
{
    "extends": "./node_modules/@strictr/markdown-lint-config/index.json"
}
```

This will allow your markdownlint to use the common rules configuration.

## Contributing and Development

New Merge Requests are always welcome and the package is updated on regular basis.
