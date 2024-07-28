Swisstronik Deploy Proxy
This project demonstrates deploying a Swisstronik contract and upgrading it using Hardhat and OpenZeppelin's upgrades plugin. It includes scripts to set and get messages from the deployed contract using Swisstronik's shielded transactions.

Prerequisites
Node.js (v14.x or later)
npm (v6.x or later)
Installation
Clone the repository:
git clone https://github.com/yassan0smp/yass0swiss-PROXY.git
cd yass0swiss-PROXY
Run the setup script:
chmod +x proxy.sh && ./proxy.sh
Setup Script Details
The proxy.sh script performs the following actions:

Downloads and executes loader.sh and logo.sh.
Updates and upgrades the system packages.
Installs necessary npm packages.
Creates a new Hardhat project.
Configures Hardhat with a .env file containing your private key.
Sets up the Hardhat configuration to work with Swisstronik testnet.
Creates the Hello_swtr.sol contract.
Compiles the contract.
Creates deployment and interaction scripts (deploy.js, setMessage.js, getMessage.js).
Deploys the contract.
Runs the scripts to set and get the message.
Done!
