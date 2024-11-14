<div align="center">

# asdf-stellar-cli [![Build](https://github.com/fnando/asdf-stellar-cli/actions/workflows/build.yml/badge.svg)](https://github.com/fnando/asdf-stellar-cli/actions/workflows/build.yml) [![Lint](https://github.com/fnando/asdf-stellar-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/fnando/asdf-stellar-cli/actions/workflows/lint.yml)

[stellar-cli](https://github.com/stellar/stellar-cli) plugin for the
[asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and
  [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add stellar-cli https://github.com/fnando/asdf-stellar-cli.git
```

stellar-cli:

```shell
# Show all installable versions
asdf list-all stellar-cli

# Install specific version
asdf install stellar-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global stellar-cli latest

# Now stellar-cli commands are available
stellar --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on
how to install & manage versions.

# Contributing

Contributions of any kind welcome! See the
[contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/fnando/asdf-stellar-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Nando Vieira](https://github.com/fnando/)
