# Issues and Solutions

## 01. AggregatorV3Interface import issue:

### Run this command:
```
forge install smartcontractkit/chainlink-brownie-contracts@1.1.1 --no-commit
```
### Add this line in **foundry.toml**:
```
remappings = ['@chainlink/contracts/=lib/chainlink-brownie-contracts/contracts/']
```
