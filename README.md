# Homebrew tap for Landin

[Landin](https://www.701.dev/) is a systems programming language. This tap's
formula installs its compiler, `refine`, with the standard library, from the
project's [GitHub releases](https://github.com/701-dev/Landin/releases).

```sh
brew install 701-dev/tap/landin   # install
brew upgrade landin               # update
brew uninstall landin             # remove
```

It runs on a Mac with Apple Silicon and on Linux, x86-64 and arm64. On macOS
`refine` links programs through the Xcode command-line tools, on Linux through
the system's GCC driver. `refine version` names the release and the directory
the library is read from.

The formula follows the releases by itself: a daily workflow points it at the
newest one.

If you installed Landin from the earlier tap `janhaan/tap`, move to this one:

```sh
brew uninstall landin
brew install 701-dev/tap/landin
```

## License

Copyright (c) 2026 Jan Haan. The tap's own files are `MIT OR Apache-2.0`: use
them under either [the MIT license](LICENSE-MIT) or [the Apache License,
Version 2.0](LICENSE-APACHE), at your option. Landin itself is licensed the
same way; see [its licence](https://github.com/701-dev/Landin/blob/main/LICENSE).
