# ERC-777

## Problems Solved

1. Hooks:
    ERC-20 tokens do not have mechanisms to notify smart contracts when tokens are received or sent.
    ERC-777 enabled hooks that allow smart contracts to react to token transfers, enabling more complex and interactive token behaviors.

2. Operator Management:
    ERC-777 includes operator functionality, allowing token holders to authorize third parties to manage their tokens, simplifying the management of tokens for various use cases.

3. Advanced Token Functionality:
    ERC-777 is built on a more advanced framework, enabling features such as granular control over transactions, batch operations, and compatibility with other standards.

## Issues Created

1. Complexity & Gas Costs:
    ERC-777 is more complex than ERC-20 increasing the risk of bugs and vulnerabilities.
    Addtionally due to its additional complexity, ERC-777 transactions are more gas-intensive, resulting in higher transaction fees.

2. Security:
    Reentrancy Attacks: The use of hooks can introduce reentrancy vulnerabilities if not carefully managed.
    Operator Management Risks: Compromised operators can lead to unauthorized management of tokens, posing a security risk.

# ERC-1363

## Problems Solved
    
1. Token Approval and Transfer in One Step:
    ERC-1363 allows tokens to be transferred and approved in a single transaction.

2. Contract Notifications
    ERC-1363 introduces transfer hooks which allow the contract to automatically handle the receipt and correctly credit the user.

# Why ERC-1363 Was Introduced

- ERC-1363 was introduced to enhance the usability of ERC-20 tokens.
- By allowing tokens to be transferred and approved in a single transaction, it streamlines interactions and reduces the complexity for users and developers.
