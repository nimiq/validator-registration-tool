# Nimiq PoS validator registration tool

This tool works by sending transactions to the Nimiq PoW blockchain in a specific
format. For further information check the [documentation](#documentation).

## Installation

Make sure you have [Node.js](https://nodejs.org) >= v16.20.2 installed.

Then navigate to this repo and execute:
```
yarn
```

## Basic usage

```
node validator.js [options]

Options:
    --help             Display this help page
    --validator        Path to the validator specification file (JSONC)
    --network          The network that should be used to register a validator. 
                       If this argument is not provided, we connect to the test network by default
```

## Documentation

Documentation is available in the [Nimiq developer center](https://www.nimiq.com/developers/build/migration-guide).