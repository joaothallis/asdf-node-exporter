# Contributing

Testing Locally:

```shell
asdf plugin test <plugin-name> <plugin-url> [--asdf-tool-version <version>] [--asdf-plugin-gitref <git-ref>] [test-command*]

#
asdf plugin test node-exporter https://github.com/joaothallis/asdf-node-exporter.git "node-exporter --help"
```

Tests are automatically run in GitHub Actions on push and PR.
