# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

asdf plugin test git-open https://github.com/tetutaro/asdf-git-open.git "git-open --help || true"
```

Tests are automatically run in GitHub Actions on push and PR.
