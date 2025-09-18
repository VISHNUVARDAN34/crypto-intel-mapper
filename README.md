# crypto-intel-mapper
FastAPI backend for Crypto Intel Mapper — fetches and displays the latest Ethereum wallet transactions using the Etherscan API. Simple, efficient, and perfect for blockchain analysis and investigation projects. Requires an Etherscan API key.

# Crypto Intel Mapper - Backend

This is the backend API service for the Crypto Intel Mapper project, built with FastAPI.  
It allows tracking Ethereum wallet transactions using the Etherscan API.

## Features

- Ping endpoint to check service status
- Retrieve recent transactions of an Ethereum wallet
- Formats transaction timestamps for readability

## Prerequisites

- Python 3.9+
- Etherscan API key (free to generate at [https://etherscan.io/apis](https://etherscan.io/apis))

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/crypto-intel-mapper-backend.git
cd crypto-intel-mapper-backend
