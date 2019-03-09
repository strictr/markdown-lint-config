# Markdown Lint Configuration

A portable markdown lint configuration.

## Installation

In order to use this configuration in your project you can run the following command:

```bash
mpm i @strictr/markdown-lint-config -D
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