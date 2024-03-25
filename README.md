<div align="center">

# asdf-coder [![Build](https://github.com/toshikish/asdf-coder/actions/workflows/build.yml/badge.svg)](https://github.com/toshikish/asdf-coder/actions/workflows/build.yml) [![Lint](https://github.com/toshikish/asdf-coder/actions/workflows/lint.yml/badge.svg)](https://github.com/toshikish/asdf-coder/actions/workflows/lint.yml)

[coder](https://coder.com/docs/v2/latest) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `unzip`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add coder
# or
asdf plugin add coder https://github.com/toshikish/asdf-coder.git
```

coder:

```shell
# Show all installable versions
asdf list-all coder

# Install specific version
asdf install coder latest

# Set a version globally (on your ~/.tool-versions file)
asdf global coder latest

# Now coder commands are available
coder version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/toshikish/asdf-coder/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [toshikish](https://github.com/toshikish/)
