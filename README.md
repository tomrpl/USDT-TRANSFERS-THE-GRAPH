# USDT-TRANSFERS-THE-GRAPH

This is my first deployment of a subgraph following the graph protocol.

This deployment here allows querying this subgraph in order to have information about any transfer of USDT tokens.

According to the following schema, one has access to the ID, the Block number, the addresses from and To and the amount of tokens.

Exchange @entity {
  # tx hash
  id: ID!

  # Block number
  block: BigInt!

  # Sender
  from: String!

  # Receiver
  to: String!

  # Amount of Tokens
  amount: BigInt!
}


All credits belongs to the tutorial of Isaac, having this github repo: https://github.com/zikyfranky.
