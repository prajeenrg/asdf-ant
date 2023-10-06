<div align="center">

# asdf-ant [![Build](https://github.com/prajeenrg/asdf-ant/actions/workflows/build.yml/badge.svg)](https://github.com/prajeenrg/asdf-ant/actions/workflows/build.yml) [![Lint](https://github.com/prajeenrg/asdf-ant/actions/workflows/lint.yml/badge.svg)](https://github.com/prajeenrg/asdf-ant/actions/workflows/lint.yml)

[ant](https://ant.apache.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `java` - Java runtime is needed, preferably Java 8 or latest.
- `JAVA_HOME`: set this environment variable to correctly run the ant tool.

# Install

Plugin:

```shell
asdf plugin add ant
# or
asdf plugin add ant https://github.com/prajeenrg/asdf-ant.git
```

ant:

```shell
# Show all installable versions
asdf list-all ant

# Install specific version
asdf install ant latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ant latest

# Now ant commands are available
ant --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/prajeenrg/asdf-ant/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Prajeen Govardhanam](https://github.com/prajeenrg/)
