<div align="center">

# asdf-argocd [![Build](https://github.com/tblaisot/asdf-argocd/actions/workflows/build.yml/badge.svg)](https://github.com/tblaisot/asdf-argocd/actions/workflows/build.yml) [![Lint](https://github.com/tblaisot/asdf-argocd/actions/workflows/lint.yml/badge.svg)](https://github.com/tblaisot/asdf-argocd/actions/workflows/lint.yml)


[argocd](https://github.com/tblaisot/asdf-argocd) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add argocd
# or
asdf plugin add argocd https://github.com/tblaisot/asdf-argocd.git
```

argocd:

```shell
# Show all installable versions
asdf list-all argocd

# Install specific version
asdf install argocd latest

# Set a version globally (on your ~/.tool-versions file)
asdf global argocd latest

# Now argocd commands are available
argocd --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tblaisot/asdf-argocd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Thomas Blaisot](https://github.com/tblaisot/)
