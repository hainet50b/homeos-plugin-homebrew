# homeos-plugin-homebrew

A [homeos](https://github.com/hainet50b/homeos) plugin for [Homebrew](https://brew.sh/), the package manager for macOS (and Linux).

## Usage

Add the plugin to your homeos repository:

```sh
homeos plugin add homebrew
```

Create a package using this plugin:

```sh
homeos package add neovim --plugin homebrew --param name=neovim
```

## Parameters

| Parameter | Description |
|-----------|-------------|
| `name` | Homebrew formula name (e.g., `neovim`, `git`) |

## Actions

| Action | Command |
|--------|---------|
| install | `brew install {{name}}` |
| update | `brew upgrade {{name}}` |
| uninstall | `brew uninstall {{name}}` |

## License

Licensed under either of

 * Apache License, Version 2.0
   ([LICENSE-APACHE](LICENSE-APACHE) or <http://www.apache.org/licenses/LICENSE-2.0>)
 * MIT license
   ([LICENSE-MIT](LICENSE-MIT) or <http://opensource.org/licenses/MIT>)

at your option.

## Contribution

Unless you explicitly state otherwise, any contribution intentionally submitted
for inclusion in the work by you, as defined in the Apache-2.0 license, shall be
dual licensed as above, without any additional terms or conditions.
