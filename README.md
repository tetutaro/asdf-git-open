<div align="center">

# asdf-git-open [![Build](https://github.com/tetutaro/asdf-git-open/actions/workflows/build.yml/badge.svg)](https://github.com/tetutaro/asdf-git-open/actions/workflows/build.yml) [![Lint](https://github.com/tetutaro/asdf-git-open/actions/workflows/lint.yml/badge.svg)](https://github.com/tetutaro/asdf-git-open/actions/workflows/lint.yml)

[git-open](https://github.com/paulirish/git-open) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `git` must already be installed.

# Install

Plugin:

```shell
asdf plugin add git-open
# or
asdf plugin add git-open https://github.com/tetutaro/asdf-git-open.git
```

git-open:

```shell
# Show all installable versions
asdf list-all git-open

# Install specific version
asdf install git-open latest

# Set a version globally (on your ~/.tool-versions file)
asdf global git-open latest

# Now git-open commands are available
git-open --help || true
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tetutaro/asdf-git-open/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Tetsutaro Maruyama](https://github.com/tetutaro/)
