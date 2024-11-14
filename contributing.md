# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

# TODO: adapt this
asdf plugin test stellar-cli https://github.com/fnando/asdf-stellar-cli.git "stellar --version"
```

Tests are automatically run in GitHub Actions on push and PR.
