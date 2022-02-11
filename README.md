<div align="center">

# asdf-regula [![Build](https://github.com/stephrobert/asdf-regula/actions/workflows/build.yml/badge.svg)](https://github.com/stephrobert/asdf-regula/actions/workflows/build.yml) [![Lint](https://github.com/stephrobert/asdf-regula/actions/workflows/lint.yml/badge.svg)](https://github.com/stephrobert/asdf-regula/actions/workflows/lint.yml)


[regula](https://regula.dev/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add regula
# or
asdf plugin add regula https://github.com/stephrobert/asdf-regula.git
```

regula:

```shell
# Show all installable versions
asdf list-all regula

# Install specific version
asdf install regula latest

# Set a version globally (on your ~/.tool-versions file)
asdf global regula latest

# Now regula commands are available
regula --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/stephrobert/asdf-regula/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Stephane ROBERT](https://github.com/stephrobert/)
