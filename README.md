# Nimiq PoS Validator Registration Tool

This command-line tool works by sending 6 transactions to the Nimiq PoW blockchain in a specific
format. For further information check the [documentation](#documentation).

## Installation

Make sure you have [Node.js](https://nodejs.org) >= v16.20.2 and [Yarn Classic](https://classic.yarnpkg.com/en/docs/install) 1.x installed.

Then navigate to this repo and install the dependencies by running:
```
yarn
```

## Basic usage

```
node validator-registration.js [options]

Options:
    --help             Display this help page
    --validator        Path to the validator specification file (JSONC)
    --network          "test" or "main" - The network that should be used to register a validator. 
                       If this argument is not provided, the tool connects to the "test" network by default
```

When run without any options, a new `validator-keys.json` file with random keys is securely generated.

## Documentation

Documentation is available in the [Nimiq developer center](https://www.nimiq.com/developers/migration/migration-validators).
