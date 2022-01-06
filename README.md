# aleph0-ledger
This repository is a ledger of bets, contracts, and other transactions.

## Proposed Workflow
1. Proposer creates a branch where the head is a *signed* commit with the
proposed contract, or transaction. The contract could be a text file in the
`contracts` directory.
2. The proposer creates a PR and sends it to the other party involved in the
transaction for review, adjustment, and approval.
3. If the other party agrees, they merge the PR to the `main` branch with a
*signed merge commit*.
