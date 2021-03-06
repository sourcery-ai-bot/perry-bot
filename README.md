# Perry Bot

[![Documentation Status](https://readthedocs.org/projects/perry-bot/badge/?version=develop)](https://perry-bot.readthedocs.io/en/develop/?badge=develop)
[![CodeFactor](https://www.codefactor.io/repository/github/shunnkou/perry-bot/badge)](https://www.codefactor.io/repository/github/shunnkou/perry-bot)
[![DeepSource](https://deepsource.io/gh/shunnkou/perry-bot.svg/?label=active+issues)](https://deepsource.io/gh/shunnkou/perry-bot/?ref=repository-badge)
[![DeepSource](https://deepsource.io/gh/shunnkou/perry-bot.svg/?label=resolved+issues)](https://deepsource.io/gh/shunnkou/perry-bot/?ref=repository-badge)
[![security: bandit](https://img.shields.io/badge/security-bandit-yellow.svg)](https://github.com/PyCQA/bandit)

A commandline self-care tracker program.

- Free software: GPL-3.0 license
- Documentation: https://perry-bot.readthedocs.io/en/develop/.

# Under active development, not functional yet

## Features

- **Commandline dashboard** to see upcoming habits and streaks.

- **Trackers**. Water, mood, and habit trackers are all supported.

- **Visualize** your tracked data with `matplotlib`.

- **Local data storage** with a SQLite database.

## Installation

Install using pipx:

```console
$ pipx install perry-bot

installed package perry-bot 0.1.0, Python 3.8.7
These apps are now globally available
  - perry-bot
done!
```

## Quickstart

See a list of commands

- `perry-bot --help`

See options and help for a specific command

- `perry-bot [COMMAND] --help`

### Commands

See the [usage](docs/usage.md#Usage) section
of the docs.

## Credits

See [credits](AUTHORS.md#credits).
