## Modified OApp

This repository modifies the OApp implementation found at `https://github.com/LayerZero-Labs/LayerZero-v2/blob/main/packages/layerzero-v2/evm/oapp/contracts/oapp/OApp.sol`


The modifications include:
- Removing constructor parameters
    - This is done so that deterministic create2 deployment is easier