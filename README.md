<div align="center">

# asdf-staticcheck [![Build](https://github.com/pbr0ck3r/asdf-staticcheck/actions/workflows/build.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-staticcheck/actions/workflows/build.yml) [![Lint](https://github.com/pbr0ck3r/asdf-staticcheck/actions/workflows/lint.yml/badge.svg)](https://github.com/pbr0ck3r/asdf-staticcheck/actions/workflows/lint.yml)

[staticcheck](https://github.com/dominikh/go-tools) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add staticcheck
# or
asdf plugin add staticcheck https://github.com/pbr0ck3r/asdf-staticcheck.git
```

staticcheck:

```shell
# Show all installable versions
asdf list-all staticcheck

# Install specific version
asdf install staticcheck latest

# Set a version globally (on your ~/.tool-versions file)
asdf global staticcheck latest

# Now staticcheck commands are available
staticcheck --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pbr0ck3r/asdf-staticcheck/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Phil Brocker](https://github.com/pbr0ck3r/)
