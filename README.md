
# SolayerStake

**Solayer Auto Stake**

## Overview

SolayerStake is a Python-based tool to automate staking on the Solana blockchain with Solayer’s Mega Validator. It allows users to programmatically create stake accounts and delegate stake to Solayer’s validator, optimizing yield through Solayer’s MEV-enabled infrastructure.

## Features

- Automatically create stake accounts on Solana
- Delegate stake to Solayer’s Mega Validator
- Uses Solana Python SDK (`solana-py`)
- Easy to configure and extend
- Supports mainnet staking with Solayer validator

## Prerequisites

- Python 3.7+
- Solana wallet keypair file or secret key
- Installed dependencies (`solana` Python package)
- SOL tokens in your wallet to cover stake amount and transaction fees

## Installation

1. Clone the repository:

```
git clone https://github.com/Caldegorn/SolayerStake.git
cd SolayerStake
```

2. (Optional) Create and activate a virtual environment:

```
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

3. Install required Python packages:

```
pip install solana
```

## Usage

1. Update `layer.py` with your wallet secret key or keypair path.

2. Configure the amount of SOL to stake.

3. Run the script to create a stake account and delegate stake to Solayer’s validator:

```
python layer.py
```

## Validator Details

- **Solayer Vote Account:** `SLaYv7tCwetrFGbPCRnqpHswG5qqKino78EYpbGF7xY`
- **Solayer Identity:** `SLAY6uN1zZpXBTfbuDDCesNmM5D288xrz8uYvfS3n41`

## Notes

- Make sure your wallet has enough SOL to cover staking amount plus transaction fees.
- Test thoroughly on Solana devnet before staking on mainnet.
- This tool requires private key management; keep your keys secure.

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
