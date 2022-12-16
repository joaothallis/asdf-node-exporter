<div align="center">

# asdf-node-exporter [![Build](https://github.com/joaothallis/asdf-node-exporter/actions/workflows/build.yml/badge.svg)](https://github.com/joaothallis/asdf-node-exporter/actions/workflows/build.yml) [![Lint](https://github.com/joaothallis/asdf-node-exporter/actions/workflows/lint.yml/badge.svg)](https://github.com/joaothallis/asdf-node-exporter/actions/workflows/lint.yml)


[node-exporter](asdf-node-exporter) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add node-exporter
# or
asdf plugin add node-exporter https://github.com/joaothallis/asdf-node-exporter.git
```

node-exporter:

```shell
# Show all installable versions
asdf list-all node-exporter

# Install specific version
asdf install node-exporter latest

# Set a version globally (on your ~/.tool-versions file)
asdf global node-exporter latest

# Now node-exporter commands are available
node-exporter --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/joaothallis/asdf-node-exporter/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [João Thallis](https://github.com/joaothallis/)
