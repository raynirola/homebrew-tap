# Ray Nirola's Homebrew tap

Install [QueueScope](https://raynirola.github.io/queuescope/), a free native macOS dashboard for BullMQ:

```sh
brew install --cask raynirola/tap/queuescope
```

Requires macOS 14 or later. The universal app supports Apple Silicon and Intel and is signed and notarized. This tap distributes the same release ZIP as GitHub Releases.

To upgrade (the app also supports updates through its menu):

```sh
brew upgrade --cask --greedy raynirola/tap/queuescope
```

Report application issues in [QueueScope](https://github.com/raynirola/queuescope/issues).

## Release maintenance

Update the cask version and SHA-256 from the published release ZIP. Keep it in sync with `distribution/Casks/queuescope.rb` in the application repository. Run `brew style` and `brew audit --cask` before publishing changes.
