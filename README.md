# Solana-MEV-Bot-Blackbook
The Solana MEV-Bot Blackbook is a historical list that stores publicly shares known MEV (Miner Extractable Value) bot addresses on the Solana blockchain. This resource aims to empower Solana developers, especially those working on trading bots, to identify and filter out these MEV bots from their applications.

## Purpose
The Solana blockchain has seen an increasing number of MEV bots that try to exploit the network for financial gain. These bots can negatively impact the performance and profitability of other trading strategies. By maintaining a public "blackbook" of known MEV bot addresses, we strive to help the Solana development community build more robust and resilient trading applications.

## How It Works
Our bots automatically monitors the Solana blockchain, identifies potential MEV bot addresses, and logs them to the mev-bot.txt file. The file is then automatically committed and pushed to this GitHub repository, allowing developers to access the latest information on active MEV bots on Solana.

## Usage
- git clone https://github.com/outsmartchad/Solana-MEV-Bot-Blackbook.git
- Access the mev-bot.txt file to view the list of known MEV bot addresses.
- Use this information to filter out these addresses from your Solana trading bot or applications.

# Up-to-date detailed txt list of mev bot address can be found here
