# Caduceus — Homebrew tap

A fast, local-first command center for macOS: launcher, clipboard history,
dictation, window management and optional local AI.

```bash
brew install --cask geowizard4645/caduceus/caduceus
```

To update: `brew upgrade --cask caduceus`.
To remove it and everything it stored: `brew uninstall --zap --cask caduceus`.

Caduceus is not notarised, so the cask clears the quarantine flag after
installing — the same thing right-click → Open does. Pass `--no-quarantine`
to skip that and approve it yourself in System Settings → Privacy & Security.

The cask is generated from [`homebrew/caduceus.rb`](https://github.com/GeoWizard4645/caduceus/blob/main/homebrew/caduceus.rb)
in the [main repository](https://github.com/GeoWizard4645/caduceus); edit it there.
