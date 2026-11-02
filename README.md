# baw-nft-auto-listing
Internal NFT auto-listing tool for a self-custody BNB Chain wallet. Max 3 listings per day, EIP-712 signed locally.
# BAW NFT Auto Listing

Internal tooling for a self-custody wallet on BNB Chain. It monitors NFT
collections we already hold and lists our own tokens on Element at fixed
prices.

- Max 3 listings per day
- ~5 API calls per order (~15/day), far below the 120/min limit
- No market making, no order spam, no third-party assets
- Orders are EIP-712 signed locally with the wallet key
- Only tokens owned by our own wallet are listed
