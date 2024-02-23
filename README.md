# Meower Admin CLI
## Description

This Python script serves as an Admin CLI (Command Line Interface) for managing profanity filters on Meower. It allows users to add or remove messages to/from either a whitelist or a blacklist.
## Prerequisites
```text
Python 3.12 or higher
MeowerBot.py version 3.x.x
```

## Installation

No installation required. Simply download the script and ensure you have the required Python version and MeowerBot.py installed.
## Usage

`python3 script_name.py [options] messages`

## Options:

- whitelist/blacklist: Specify whether to target the whitelist or the blacklist.
- add/remove: Specify whether to add or remove messages.
- --username USERNAME: MeowerBot username.
- --password PASSWORD: MeowerBot password.
- --api API_URL: URL of the Meower API. Default is https://api.meower.org/.
- --websocket WS_URL: Websocket URL of the Meower server. Default is wss://server.meower.org.

## Arguments:

- messages: Messages you want to perform actions on.

## Example:

`./admin --username="" --password="" whitelist add "hello there" "goodbye"`
