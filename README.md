# Vyomi Homebrew Tap

Homebrew formulae for Vyomi — local multi-cloud simulator (AWS / GCP / Azure).

## Install

```bash
brew tap vyomi-cloud/tap
brew install cloud-learn
```

Then start the simulator:

```bash
cloud-learn up
open http://localhost:9000
```

## What you get

| Command | What it does |
|---|---|
| `brew install cloud-learn` | Installs the launcher CLI |
| `cloud-learn up` | Starts the Docker-based appliance (~30 s first time) |
| `cloud-learn down` | Stops everything |
| `cloud-learn status` | Shows running containers |
| `cloud-learn upgrade` | Pulls the latest image |

## Source

The Formula is auto-bumped by [vyomi-cloud/appliance](https://github.com/vyomi-cloud/appliance)'s
release workflow on every `v*.*.*` tag.
