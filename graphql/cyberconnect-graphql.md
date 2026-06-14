# CyberConnect GraphQL API

The CyberConnect GraphQL API is the primary interface for the CyberConnect Web3 social graph protocol. It exposes a comprehensive set of queries and mutations for interacting with decentralized social graph data, including user identities, follower and following relationships, social connections, and personalized recommendations. The API supports both Ethereum (ETH) and Solana networks and uses a namespace-based system that allows applications to isolate and manage their own social graph data independently.

The API is organized into two main operation categories. Queries allow developers to retrieve social graph data such as user identity profiles (address, ENS domain, avatar, social links), follow status between two addresses, paginated follower and following lists, rankings of influential addresses, and connection recommendations. Mutations enable write operations including authentication via wallet signatures, following and unfollowing addresses, registering signing keys, setting aliases on connections, and updating profile metadata. Authentication is performed by submitting a wallet signature to the `auth` mutation, which returns a JWT-format `authToken` that must be included in subsequent authenticated requests.

The endpoint for the CyberConnect Indexer GraphQL API was `https://api.cybertino.io/connect/` with an interactive GraphiQL playground available at `https://api.cybertino.io/connect/graphiql`. CyberConnect has since rebranded to Cyber.co and the protocol has evolved; the current developer documentation is maintained at `https://docs.cyber.co/`. The legacy GraphQL indexer documentation remains available at the Vercel-hosted docs site and through the GitHub repository for `cyberconnect-docs`.

**Endpoint:** https://api.cybertino.io/connect/

**Documentation:** https://cyberconnect-docs-v2.vercel.app/

**References:**
- Documentation: https://cyberconnect-docs-v2.vercel.app/
- GettingStarted: https://cyberconnect-docs-v2.vercel.app/guides/authentication/api-key
