<div align="center">

# asdf-zizmor [![Build](https://github.com/bryanwweber/asdf-zizmor/actions/workflows/build.yml/badge.svg)](https://github.com/bryanwweber/asdf-zizmor/actions/workflows/build.yml) [![Lint](https://github.com/bryanwweber/asdf-zizmor/actions/workflows/lint.yml/badge.svg)](https://github.com/bryanwweber/asdf-zizmor/actions/workflows/lint.yml)

[zizmor](https://woodruffw.github.io/zizmor/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add zizmor
# or
asdf plugin add zizmor https://github.com/bryanwweber/asdf-zizmor.git
```

zizmor:

```shell
# Show all installable versions
asdf list-all zizmor

# Install specific version
asdf install zizmor latest

# Set a version globally (on your ~/.tool-versions file)
asdf global zizmor latest

# Now zizmor commands are available
zizmor --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/bryanwweber/asdf-zizmor/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Bryan Weber](https://github.com/bryanwweber/)
