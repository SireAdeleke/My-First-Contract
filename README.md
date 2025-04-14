This repository contains an **ERC-20 token contract** written in Solidity, which follows the ERC-20 standard for fungible tokens.

The contract implements functions such as:
- `totalSupply`
- `balanceOf`
- `transfer`

The contract is deployed on the **Somnia Testnet**
## How to Deploy

1. **Go to Remix IDE**: Visit [Remix](https://remix.ethereum.org), open the `MyToken.sol` file from this repository.
2. **Compile**: Set Solidity version `0.8.26` and click **Compile**.
3. **Deploy**:
   - Use **Injected Web3** for the environment.
   - Ensure you're connected to the **Somnia Testnet**.
   - Deploy by providing an initial supply (e.g., 1,000,000 tokens).

---

## Testing

After deployment, you can interact with the contract by:
- Checking the total supply using `totalSupply`.
- Checking the balance of any address using `balanceOf`.
- Transferring tokens using the `transfer` function.
