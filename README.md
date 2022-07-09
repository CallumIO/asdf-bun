<div align="center">

# asdf-bun [![Lint](https://github.com/CallumIO/asdf-bun/actions/workflows/lint.yml/badge.svg)](https://github.com/CallumIO/asdf-bun/actions/workflows/lint.yml)


[bun](https://github.com/CallumIO/asdf-bun) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `bsdtar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add bun
# or
asdf plugin add bun https://github.com/CallumIO/asdf-bun.git
```

bun:

```shell
# Show all installable versions
asdf list-all bun

# Install specific version
asdf install bun latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bun latest

# Now bun commands are available
bun --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/CallumIO/asdf-bun/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Callum Leslie](https://github.com/CallumIO/)
