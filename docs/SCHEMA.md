# Token Metadata Schema (v0)
Minimal fields we accept in Day-1 pilots.

Required:
- name: string
- symbol: string
- decimals: number
- mints:
  - devnet: string (base58 mint address)
  - testnet: string
  - mainnet: string
Optional:
- logoURI: string (https URL)
- tags: [string]
- description: string
- extensions: { website?: string, twitter?: string, coingeckoId?: string }

See /metadata/_templates/token.example.json
