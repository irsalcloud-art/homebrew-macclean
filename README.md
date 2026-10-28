# homebrew-macclean

Homebrew tap for [MacClean](https://github.com/irsalcloud-art/Clean_mac), a storage analyzer, safe developer-cache cleaner and system monitor for macOS.

## Install

```bash
brew install irsalcloud-art/macclean/macclean
```

The formula installs the universal (arm64 + x86_64) release binary, pinned to the SHA-256 published in the release's `SHA256SUMS`. It requires macOS 15 (Sequoia) or later, the minimum MacClean supports, and Homebrew needs up-to-date Command Line Tools to install it.

## Uninstall

```bash
brew uninstall macclean
```

```bash
brew untap irsalcloud-art/macclean
```

## Maintaining

The formula's source of truth is [`packaging/homebrew/macclean.rb`](https://github.com/irsalcloud-art/Clean_mac/blob/main/packaging/homebrew/macclean.rb) in the main repository; copy it here after each release. Report problems with MacClean itself in [Clean_mac's issues](https://github.com/irsalcloud-art/Clean_mac/issues).

MacClean is licensed under either of MIT or Apache-2.0, at your option.
