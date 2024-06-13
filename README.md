# subnet-using-Avalanche

## Introduction

Welcome to the DeFi Kingdom Clone Setup Guide! This repository equips you with all the necessary resources and step-by-step instructions to establish your own DeFi Kingdom clone on a custom EVM subnet using the Avalanche network.

## Prerequisites

Before you begin, ensure you have the following:

- Node.js and npm installed
- MetaMask installed in your browser
- Basic understanding of Solidity and smart contracts
- Familiarity with Avalanche CLI and Remix IDE

## Setup Instructions

### 1. Set up Your EVM Subnet

Follow these steps to create a custom EVM subnet on the Avalanche network:

1. Install the Avalanche CLI:
   ```sh
   npm install -g avalanche
   ```

2. Initialize your subnet:
   ```sh
   avalanche subnet create <subnet-name>
   ```

3. Customize the subnet configuration as per your requirements.

### 2. Define Your Native Currency

Configure your own native currency within your EVM subnet setup. This currency will serve as the in-game currency for your DeFi Kingdom clone.

### 3. Connect to MetaMask

To integrate your EVM subnet with MetaMask, follow these steps:

1. Open MetaMask and navigate to `Settings` > `Networks` > `Add Network`.
2. Enter the network details based on your EVM subnet configuration.
3. Save the network settings and switch to it.

### 4. Deploy Basic Building Blocks

Utilize Solidity and Remix to deploy essential components of your game:

1. Access [Remix IDE](https://remix.ethereum.org/).
2. Connect Remix to your MetaMask wallet by selecting `Injected Web3` as the environment.
3. Write and compile your Solidity smart contracts.
4. Deploy the contracts using the Remix interface.

## Testing

After deploying your contracts, proceed with testing your application:

1. Interact with your deployed contracts using Remix.
2. Deploy tokens, liquidity pools, and other necessary components.
3. Validate the functionality of your game's rules and interactions.

## Useful Links

- [Avalanche Documentation](https://docs.avax.network)
- [MetaMask](https://metamask.io/)
- [Remix IDE](https://remix.ethereum.org/)

## Contributing

Contributions are encouraged! Feel free to open issues or pull requests for any enhancements or additions you'd like to propose.

## License

This project is licensed under the MIT License. For more details, refer to the [LICENSE](LICENSE) file.

---

By following these comprehensive instructions, you'll successfully set up your own DeFi Kingdom clone on a custom EVM subnet using the Avalanche network. Start building your DeFi empire today!
