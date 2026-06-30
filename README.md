# homebrew-SLMCortex

Homebrew tap for installing Slm Cortex on macOS and Linux.

## Install

```bash
brew tap alvarolorentedev/SLMCortex
brew install slmcortex
```

Or install directly from the tap in one command:

```bash
brew install alvarolorentedev/SLMCortex/slmcortex
```

This installs both public launchers:

```bash
slmcortex --help
slmcortex-composer --help
```

## Upgrade

```bash
brew update
brew upgrade slmcortex
```

## Notes

- The formula works with Homebrew on macOS and Linuxbrew on Linux.
- The formula currently installs the base Composer-first CLI path only.
- Optional runtime backends can be provisioned after install from the CLI itself.