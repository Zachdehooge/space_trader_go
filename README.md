# 🚀 Space Trader API 🛠️ [WIP]
[![Build Status](https://www.travis-ci.com/HOWZ1T/space_trader.svg?branch=master)](https://www.travis-ci.com/HOWZ1T/space_trader)
[![codecov](https://codecov.io/gh/HOWZ1T/space_trader/branch/master/graph/badge.svg?token=4L7QO7TFDX)](https://codecov.io/gh/HOWZ1T/space_trader)
[![Go Report Card](https://goreportcard.com/badge/github.com/HOWZ1T/space_trader)](https://goreportcard.com/report/github.com/HOWZ1T/space_trader)

Space Traders is an API game where players explore the stars in order to exploit for it's riches.

More info available [here](https://spacetraders.io/).

This project provides a golang wrapper for the api.

## 🛠️ Work In Progress
Notice this package is in it's alpha stage and is subject to api changes.

## 🔧 Documentation
- [Event Reference](EVENTS.md)
- [Go Docs](https://pkg.go.dev/github.com/HOWZ1T/space_trader)

## 💾 Models
Most of the objects have been modelled and can be accessed through the model package.

The methods in this wrapper return the relevant model.

## 📔 Examples
- 🎓 [Quick Start](examples/QUICKSTART.md)

## 📝 TODO
- [ ] More Examples
  - [x] Quick Start
- [x] Continuous Integration
- [ ] Unit Tests (Reach at least 80% coverage)
- [x] Documentation
- [x] Event System
- [ ] Events:
  - [ ] Low Fuel
  - [ ] Out Of Fuel
  - [ ] Low Cargo Space
  - [ ] Cargo Full
  - [ ] Low Credits
  - [ ] Out Of Credits
  - [ ] Loan Due
