# SelfDestruct
This repo is a simple demonstration of how to deploy a self-destruct smart contract. This can be useful for forcing ether into a compromised wallet infected by a sweeper bot.
# How to Deploy
STEP 1
Copy and paste the Force.sol file into your workspace at remix.ethereum.org

STEP 2
Compile the contract using the appropraite compiler version.

STEP 3
Connect your Metamask wallet via 'Injected Web3 Provider'.
Note that you must specify the destination address that will receive all available ether in the smart contract before you click DEPLOY

STEP 4 
Fund the contract with the required amount of ETH you want to FORCE into the compromised wallet.

NOTE!!!
Forcing ETH via Self-Destruct will be exceuted as an Internal Transaction therefore it cannot be seen by the sweeper bot attached to the compromised wallet.

# Useful Links
Contract Deployment Hash ( Goerli Testnet Only )
https://goerli.etherscan.io/tx/0x0bce3264dd34585b5a187dc0f15ffd3dcfcdf4aec9939fd0589eb9629f5855e5

Sourcify Plugin Repo
https://repo.sourcify.dev/contracts/full_match/5/0x93C33bC20C7567b584E0736C6c5455F5674eC797/sources/contracts/

Self-Destruct Transaction Hash
https://goerli.etherscan.io/tx/0x629d314ad53d93be41b4720c1eaba9427a426ee0fb7fb2efdaae3f95ce1e8dcb
