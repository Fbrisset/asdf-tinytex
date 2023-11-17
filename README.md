<div align="center">

# asdf-tinytex [![Build](https://github.com/Fbrisset/asdf-tinytex/actions/workflows/build.yml/badge.svg)](https://github.com/Fbrisset/asdf-tinytex/actions/workflows/build.yml) [![Lint](https://github.com/Fbrisset/asdf-tinytex/actions/workflows/lint.yml/badge.svg)](https://github.com/Fbrisset/asdf-tinytex/actions/workflows/lint.yml)

[tinytex](https://github.com/rstudio/tinytex) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add tinytex
# or
asdf plugin add tinytex https://github.com/Fbrisset/asdf-tinytex.git
```

tinytex:

```shell
# Show all installable versions
asdf list-all tinytex

# Install specific version
asdf install tinytex latest

# Set a version globally (on your ~/.tool-versions file)
asdf global tinytex latest

# Now tinytex commands are available
tex --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/Fbrisset/asdf-tinytex/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Florian Brisset](https://github.com/Fbrisset/)
