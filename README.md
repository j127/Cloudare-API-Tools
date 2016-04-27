# Cloudflare API Tools

WARNING: this script is in the early stages and isn't well-tested. Be sure you understand what it does and how it works before you use it.

A simple command line utility to manage development mode and cache clearing on Cloudflare.

Python 3.

## Installation

* Be sure that requests is installed.
* Alias `python3 /path/to/cf.py` to `cf` or whatever you want.
* Put API credentials in `config_example.py` and rename it to `config.py`.

## Usage

Clear all caches:

    $ cf -z example.com -c

Turn on development mode:

    $ cf -z example.com -d on

Turn off development mode:

    $ cf -z example.com -d off

RTM:

    $ cf -h

## TODO

1. Make it interactive by loading all of the account's domains with a numbered menu.
