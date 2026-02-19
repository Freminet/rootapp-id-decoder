# root id decoder

A web-based tool to decode Root user IDs and extract account creation timestamps. Root uses snowflake-like IDs that embed information about the account

![Root ID Decoder Screenshot](https://i.imgur.com/rhPI227.png)

## website

[visit it here](https://skirk.one/root/)

## features

well let's see:
- account age
- exact unix timestamp
- dark mode??
- cute anime girl

## how it works

Root user IDs are publicly visible identifiers (accessible via developer mode) that follow a snowflake-like format with embedded timestamp information. This tool:

1. Takes a Root user ID as input
2. Performs mathematical operations to extract the embedded timestamp
3. Displays the account creation date and age

No data is sent to any server, all calculations happen locally in your browser
