# Redox Tap

## How do I install these formulae and casks?

`brew install --cask redox/tap/<cask>`

Or `brew tap redox/tap` and then `brew install --cask <cask>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "redox/tap"
cask_args appdir: "/Applications"
cask "<cask>"
```

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
