# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test torii . --asdf-tool-version 1.6.0
```

Tests are automatically run in GitHub Actions on push and PR.
