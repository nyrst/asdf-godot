<div align="center">

# asdf-godot ![Build](https://github.com/nyrst/asdf-godot/workflows/Build/badge.svg) ![Lint](https://github.com/nyrst/asdf-godot/workflows/Lint/badge.svg)

[godot](https://godotengine.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `unzip`.

# Install

Plugin:

```shell
asdf plugin add godot https://github.com/nyrst/asdf-godot.git
```

godot:

```shell
# Show all installable versions
asdf list-all godot

# Install specific version
asdf install godot latest

# Set a version globally (on your ~/.tool-versions file)
asdf global godot latest

# Now godot commands are available
godot --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/nyrst/asdf-godot/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Siegfried Ehret](https://github.com/SiegfriedEhret/)
