# CyberConnect

CyberConnect is a Web3 social graph protocol that enables developers to build decentralized social applications. The protocol provides GraphQL and SDK-based APIs for accessing social graphs, profiles, followers, connections, and recommendation data across Ethereum and Solana networks. Users own their social identities, content, and connections.

## APIs

### GraphQL Indexer API

- **Endpoint:** `https://api.cybertino.io/connect/`
- **Playground:** `https://api.cybertino.io/connect/graphiql`
- **Dev Testnet:** `https://api.cyberconnect.dev/testnet/`
- **Authentication:** `X-API-KEY` header with JWT API key

Available queries:

- `identity` - Get address identity, domain (ENS/Solana), avatar, social accounts, follower/following/friend lists
- `connections` - Check connection status between a source address and up to 5000 target addresses
- `recommendations` - Get personalized follow suggestions for an address

### JavaScript SDK

- **Package:** `@cyberlab/cyberconnect`
- **Install:** `npm install @cyberlab/cyberconnect`
- **GitHub:** https://github.com/cyberconnecthq/js-cyberconnect

The SDK provides `connect()` and `disconnect()` methods for writing follow/unfollow relationships to the decentralized social graph. It supports Ethereum and Solana and uses namespace-based data isolation.

## Resources

- **Developer Docs:** https://cyberconnect-docs-v2.vercel.app/
- **Current Docs (Cyber L2):** https://docs.cyber.co/
- **GitHub Org:** https://github.com/cyberconnecthq
- **Discord:** https://discord.com/invite/cyberconnect
- **Twitter:** https://twitter.com/CyberConnectHQ
- **Blog:** https://cyber.co/blog
- **Starter Project:** https://github.com/cyberconnecthq/cyberconnect-starter

## About

CyberConnect evolved into Cyber, an Ethereum Layer 2 network (OP Stack, powered by EigenLayer) optimized for social applications and launched on mainnet in 2024. The $CYBER token is used for staking, governance, and content monetization. The CyberAI suite provides crypto intelligence APIs for builders and agents.
