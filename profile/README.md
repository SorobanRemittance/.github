# UtilityX Remittance Layer

A Pan-African remittance infrastructure powered by Stellar and Soroban smart contracts.

## Overview

UtilityX enables instant, low-cost cross-border transfers across Africa using USDC settlement rails.

Users can:
- Send money internationally
- Cash out to local banks/mobile money
- Store value in stablecoins
- Trade utility assets
- Access borderless payments

## Features

- Stellar-based settlement
- Soroban smart contracts
- USDC remittance rail
- Agent cash-in/cash-out
- Mobile money integrations
- Multi-currency support
- Escrow settlement
- Fee routing engine
- Compliance monitoring

## Tech Stack

### Frontend
- React Native
- Next.js

### Backend
- NestJS
- PostgreSQL
- Redis

### Blockchain
- Stellar
- Soroban
- Rust smart contracts

## Smart Contracts

### Escrow Contract
Handles secure remittance settlement.

### Fee Router
Splits protocol fees automatically.

### Liquidity Pool
Provides FX liquidity for corridors.

### Compliance Contract
Validates transactions and risk rules.

## Architecture

User → API → Soroban Contracts → Stellar → Offramps

## Roadmap

### MVP
- Wallets
- USDC transfers
- Nigeria corridor
- Agent network

### Phase 2
- Multi-country support
- Merchant APIs
- Liquidity pools

### Phase 3
- Utility marketplace
- DAO governance
- Pan-African settlement network

## Security

- Multi-sig treasury
- AML monitoring
- Transaction auditing
- Encrypted wallets

## License

MIT
