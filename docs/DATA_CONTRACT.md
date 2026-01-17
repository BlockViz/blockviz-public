# BlockViz Data Contract (Public)

This document defines a minimal public payload shape used to describe a **blockchain value flow**.
It is intentionally small and does not describe BlockViz internal storage or implementation.

## Concepts

- **flow_id**: identifier for a flow artifact
- **chain**: blockchain network identifier (e.g., ethereum)
- **nodes**: entities (addresses, contracts, exchanges)
- **edges**: transfers between nodes with amounts and timestamps

See `api/flow.schema.json` and `examples/sample-flow.json`.
