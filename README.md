# Etw35 Tap
This is a tap for the [Homebrew package manager](https://github.com/Homebrew/brew) package manager. Some packages, e.g., Mrbayes, are just updated or modified versions of those from [Homebrew Core](https://github.com/homebrew/homebrew-core). I've put those here because, although they work, I have not yet gone through Homebrew's submission process.

To install Mrbayes 3.2.9 with OpenMPI and Beagle support, run:
brew install etw35/tap/mrbayes-mpi-beagle

## How do I install these formulae?

`brew install etw35/tap/<formula>`

Or `brew tap etw35/tap` and then `brew install <formula>`.

Or, in a `brew bundle` `Brewfile`:

```ruby
tap "etw35/tap"
brew "<formula>"
```

## Installing MrBayes
To install Mrbayes 3.2.9 with OpenMPI and Beagle support

`brew install etw35/tap/mrbayes-mpi-beagle`

This version can coexist with mb and mb-mpi from Homebrew Core.

## Documentation

`brew help`, `man brew` or check [Homebrew's documentation](https://docs.brew.sh).
