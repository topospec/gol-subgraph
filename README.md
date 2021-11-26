# GolSwap Subgraph

TheGraph exposes a GraphQL endpoint to query the events and entities within the Binance Smart Chain and GolFinance ecosystem.

## To setup and deploy

1. Run the `yarn run codegen` command to prepare the TypeScript sources for the GraphQL (generated/*).

2. Run the `yarn run build` command to build the subgraph, and check compilation errors before deploying.

3. Run `graph auth https://api.thegraph.com/deploy/ '<ACCESS_TOKEN>'`

4. Deploy via `yarn run deploy --ipfs https://api.thegraph.com/ipfs/ --debug`.
