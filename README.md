# Solana NFT Contract

A Rust-based Solana smart contract (program) for minting NFTs on the Solana blockchain.

## Overview

This repository contains a Solana program written in Rust that implements NFT (Non-Fungible Token) minting functionality. The contract follows Solana's programming model and token standards.

## Features

- NFT minting functionality
- Written in Rust
- Implements Solana Program interface
- Follows Metaplex NFT standards

## Prerequisites

- Rust (latest stable version)
- Solana Tool Suite
- Anchor Framework (optional)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/devincredible/solana-nft.git
cd solana-nft
```

2. Install dependencies:

```bash
cargo build
```

## Building

To build the program:

```bash
cargo build-bpf
```

## Testing

To run the tests:

```bash
cargo test
```

## Deployment

1. Start a local Solana validator (for testing):

```bash
solana-test-validator
```

2. Deploy the program:

```bash
solana program deploy target/deploy/solana_nft.so
```

## Project Structure

```
solana-nft/
├── src/           # Source code directory
├── Cargo.toml     # Rust package manifest
└── README.md      # This file
```

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments

- Solana Foundation for their documentation and tools
- Metaplex for NFT standards
