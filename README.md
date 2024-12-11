<div align="center">

# asdf-multitail [![Build](https://github.com/rmgpinto/asdf-multitail/actions/workflows/build.yml/badge.svg)](https://github.com/rmgpinto/asdf-multitail/actions/workflows/build.yml) [![Lint](https://github.com/rmgpinto/asdf-multitail/actions/workflows/lint.yml/badge.svg)](https://github.com/rmgpinto/asdf-multitail/actions/workflows/lint.yml)

[multitail](https://github.com/rmgpinto/multitail) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add multitail
# or
asdf plugin add multitail https://github.com/rmgpinto/asdf-multitail.git
```

multitail:

```shell
# Show all installable versions
asdf list-all multitail

# Install specific version
asdf install multitail latest

# Set a version globally (on your ~/.tool-versions file)
asdf global multitail latest

# Now multitail commands are available
multitail --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rmgpinto/asdf-multitail/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ricardo Pinto](https://github.com/rmgpinto/)
