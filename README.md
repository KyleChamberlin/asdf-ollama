<div align="center">

# asdf-ollama [![Build](https://github.com/KyleChamberlin/asdf-ollama/actions/workflows/build.yml/badge.svg)](https://github.com/KyleChamberlin/asdf-ollama/actions/workflows/build.yml) [![Lint](https://github.com/KyleChamberlin/asdf-ollama/actions/workflows/lint.yml/badge.svg)](https://github.com/KyleChamberlin/asdf-ollama/actions/workflows/lint.yml)

[ollama](https://ollama.ai) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add ollama
# or
asdf plugin add ollama https://github.com/KyleChamberlin/asdf-ollama.git
```

ollama:

```shell
# Show all installable versions
asdf list-all ollama

# Install specific version
asdf install ollama latest

# Set a version globally (on your ~/.tool-versions file)
asdf global ollama latest

# Now ollama commands are available
ollama -v
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/KyleChamberlin/asdf-ollama/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kyle Chamberlin](https://github.com/KyleChamberlin/)
