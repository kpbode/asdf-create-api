<div align="center">

# asdf-create-api [![Build](https://github.com/kpbode/asdf-create-api/actions/workflows/build.yml/badge.svg)](https://github.com/kpbode/asdf-create-api/actions/workflows/build.yml) [![Lint](https://github.com/kpbode/asdf-create-api/actions/workflows/lint.yml/badge.svg)](https://github.com/kpbode/asdf-create-api/actions/workflows/lint.yml)

[create-api](https://github.com/CreateAPI/CreateAPI) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add create-api
# or
asdf plugin add create-api https://github.com/kpbode/asdf-create-api.git
```

create-api:

```shell
# Show all installable versions
asdf list-all create-api

# Install specific version
asdf install create-api latest

# Set a version globally (on your ~/.tool-versions file)
asdf global create-api latest

# Now create-api commands are available
create-api --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kpbode/asdf-create-api/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Karl Bode](https://github.com/kpbode/)
