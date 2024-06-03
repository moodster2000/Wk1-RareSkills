# Why does the SafeERC20 program exist and when should it be used?

## Why?
- SafeERC20 wraps ERC-20 operations in functions that include proper checks and error handling, preventing these common mistakes.

## When?
- When your contract is designed to work with external tokens that you do not control, using SafeERC20 helps ensure that your contract can handle tokens with non-standard behavior or potential bugs in a robust manner.
- In complex contracts that involve multiple token transfers or interactions, SafeERC20 can help reduce the risk of failure and ensure that all operations complete successfully.