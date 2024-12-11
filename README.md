## RANA Stablecoin

This is a stablecoin project that is pegged to the value of the US dollar.

### Characteristics

1. **Relative Stability**: The value of the RANA stablecoin is pegged to the value of the US dollar.
   This will be using the Chainlink Oracle to get the current value of the ETH/USD & BTC/USD to get the current value of the US dollar.
2. **Algorithmic**: Minting will be Algorithmic, and the supply will be adjusted based on the demand.
   People can only mint the stablecoin with enough collateral (coded in the smart contract).
3. **Exogenous**: The RANA stablecoin is not backed by any physical asset, but by the value of the US dollar.
   This is to ensure that the value of the stablecoin is not affected by the value of the collateral<>. We will use these collaterals: wETH and wBTC.

### Requirements

- @openzeppelin/contracts
- @chainlink/contracts
