# WhatsOnChain

A blockchain explorer and REST API for the BSV and BTC networks. Provides access to blocks, transactions, address activity, on-chain data, stats, and more — plus transaction broadcasting for BSV. Operates on independent infrastructure accompanying [whatsonchain.com](https://whatsonchain.com).

## Supported Networks

- **BSV** — Mainnet and Testnet
- **BTC** — Mainnet

## Authentication & Rate Limits

| Tier       | Rate Limit         | Auth Required |
|------------|--------------------|---------------|
| Free       | 3 requests/sec     | No            |
| Paid       | 10–40 requests/sec | Yes           |
| Enterprise | Custom             | Yes           |

Paid plans are available through the [Teranode Group Platform](https://console.teranodegroup.com). Pass your key via the `Authorization` header:

```
curl -H 'Authorization: mainnet_YOUR_API_KEY' \
  https://api.whatsonchain.com/v1/bsv/main/chain/info
```

Free-tier users should display the **Powered by WhatsOnChain** logo in their applications.

## API Documentation

Full REST API reference with endpoints for blocks, transactions, addresses, UTXOs, scripts, exchange rates, stats, WebSockets, and token standards:

- [API Docs](https://docs.whatsonchain.com)
- [Postman Collection](https://docs.whatsonchain.com) — available for testing

## Support

- [WoC Devs Telegram](https://t.me/WoCdevs) — developer community and support
