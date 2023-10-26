# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test staticcheck https://github.com/pbr0ck3r/asdf-staticcheck.git "staticcheck --version"
```

Tests are automatically run in GitHub Actions on push and PR.
