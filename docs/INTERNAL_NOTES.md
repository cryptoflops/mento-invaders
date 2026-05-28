# Internal Developer Notes

- Tested cUSD approve + deposit flow on Celo mainnet. Gas estimates stable at ~45k per tx.
- Reviewed WagmiProvider config. The QueryClient should probably have a longer gcTime for balance queries.
