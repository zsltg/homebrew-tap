# zsltg/homebrew-tap

Homebrew tap for the command-line tools of [zsltg](https://github.com/zsltg).

## Install

```sh
brew install zsltg/tap/<name>
```

This command adds the tap and installs the cask. To upgrade an installed tool to its latest release:

```sh
brew upgrade <name>
```

## Casks

| Name | Description | Platforms |
|---|---|---|
| [iq](https://github.com/zsltg/iq) | jq for NoSQL databases | macOS, Linux (Intel, ARM) |

The casks are in `Casks/`. The release workflow of each tool writes its cask with GoReleaser. Do not edit a cask by hand, because the next release replaces it.

## Problems

Report a problem in the issue tracker of the tool, not in this repository.
