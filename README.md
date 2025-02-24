Decentralized Exchange
This is a decentralized exchange (DEX) project that enables secure and efficient token trading on the blockchain. Built with Solidity for smart contracts, Hardhat for development, and integrated with frontend technologies.

🚀 Features
Smart Contracts: The core functionality is powered by Solidity smart contracts (e.g., CustomTokenExchange, Exchange, Token).
Deploy & Seed: Includes deployment scripts (1_deploy.js, 2_Seed_Exchange.js) and test scripts to interact with the contracts.
Public Interface: The frontend includes a basic interface for users to interact with the exchange.
Testing: Tests for token and exchange contract interactions in the test/ directory.
📂 Project Structure
bash
Copy
Edit
project.m/
│── contracts/                # Smart contract files (Solidity)
│   ├── CustomTokenExchange.sol
│   ├── Exchange.sol
│   ├── IERC20.sol
│   ├── SocialMessage.sol
│   ├── SocialNetwork.sol
│   └── Token.sol
│── hardhat.config.js         # Hardhat configuration file
│── OldCod/                   # Backup and legacy files
│── package-lock.json         # Dependency lock file
│── package.json              # Project dependencies and scripts
│── public/                   # Static assets (favicon, images)
│── README.md                 # Project documentation
│── scripts/                  # Deployment and utility scripts
│── src/                      # Frontend React code
│── test/                     # Smart contract test files
└── .gitignore                # Git ignore file
📧 Technologies Used
Solidity: Smart contract development for DEX functionality.
Hardhat: Ethereum development environment for deploying and testing smart contracts.
React: Frontend for users to interact with the DEX.
JavaScript: Used for dynamic functionality and testing scripts.
🛠️ How to Run Locally
Clone the repository:
bash
Copy
Edit
git clone https://github.com/Bladecmd/Project.m-decentralized-exchange.git
Install dependencies:
bash
Copy
Edit
npm install
Run Hardhat:
bash
Copy
Edit
npx hardhat run scripts/1_deploy.js --network <network_name>
For frontend:
bash
Copy
Edit
npm start
Access the exchange at http://localhost:3000.

🔗 Connect with Me
GitHub: BladeCMD
Twitter: @
TikTok: @
