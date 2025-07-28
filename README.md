<div align="center">

# asdf-torii [![Build](https://github.com/dojoengine/asdf-torii/actions/workflows/build.yml/badge.svg)](https://github.com/dojoengine/asdf-torii/actions/workflows/build.yml) [![Lint](https://github.com/dojoengine/asdf-torii/actions/workflows/lint.yml/badge.svg)](https://github.com/dojoengine/asdf-torii/actions/workflows/lint.yml)

[torii](https://book.dojoengine.org/toolchain/torii) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `unzip` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add torii
# or
asdf plugin add torii https://github.com/dojoengine/asdf-torii.git
```

torii:

```shell
# Show all installable versions
asdf list all torii

# Install specific version
asdf install torii latest

# Set a version globally (on your ~/.tool-versions file)
asdf global torii latest

# Now torii commands are available
torii --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/dojoengine/asdf-torii/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [dojoengine](https://github.com/dojoengine/)
