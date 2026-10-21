# Yahoo Fantasy ChatGPT Bridge

A personal project for connecting my Yahoo Fantasy Football league data to ChatGPT for analysis and roster management support.

## Purpose

This application is intended for personal use with my own Yahoo Fantasy Football account and league data.

The goal is to securely retrieve fantasy football information such as:

- League settings
- Team rosters
- Weekly matchups
- Standings
- Player scoring
- Transactions
- Waiver information
- Available players

The data will be used to help analyze lineup decisions, waiver-wire options, trades, and weekly matchups.

## Access

The application will use Yahoo OAuth 2.0 to access authorized Yahoo Fantasy Sports data.

Initial development will be read-only. No roster moves, transactions, or lineup changes will be made automatically.

## Privacy and Security

Yahoo credentials, OAuth tokens, and other sensitive information will not be stored in this public repository.

Sensitive configuration values will be stored locally using environment variables and excluded from Git through `.gitignore`.

## Status

This project is currently under development for personal use.

## Disclaimer

This project is not affiliated with, endorsed by, or sponsored by Yahoo or OpenAI.
