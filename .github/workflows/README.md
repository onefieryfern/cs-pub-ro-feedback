# GitHub Actions

## Markdown linter

The Markdown linter is [`markdownlint-cli2`](https://github.com/DavidAnson/markdownlint-cli2).

### Configuration

The config file is `.markdownlint-cli2.jsonc`. Information on the supported rules can be found [in the documentation](https://github.com/DavidAnson/markdownlint/blob/main/doc/Rules.md).

Information on configuring the GitHub action can be found [on the action's page](https://github.com/marketplace/actions/markdownlint-cli2-action).

### Running locally

Install `markdownlint-cli2` as described [in its README](https://github.com/DavidAnson/markdownlint-cli2#install).

To use, run the following in the cloned repository's root:

```sh
markdownlint-cli2 "**/*.md"
```

It will automatically use the configuration file and lint all Markdown files.
