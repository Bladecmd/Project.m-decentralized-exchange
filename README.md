Decentralized Exchange
This project is a decentralized exchange (DEX) built using Solidity for smart contracts, Hardhat for development, and React for the frontend. It enables token trading and blockchain interaction.

🚀 Features
Smart Contracts: Core functionality powered by Solidity (CustomTokenExchange, Exchange, Token).
Deployment: Includes deployment scripts (1_deploy.js, 2_Seed_Exchange.js).
Public Interface: Frontend for user interaction with the exchange.
Testing: Test files to verify smart contract functions (test/).
📂 Project Structure
bash
Copy
Edit
project.m/
├── contracts/                # Smart contracts (Solidity)
│   ├── CustomTokenExchange.sol
│   ├── Exchange.sol
│   ├── IERC20.sol
│   ├── SocialMessage.sol
│   ├── SocialNetwork.sol
│   └── Token.sol
├── hardhat.config.js         # Hardhat configuration file
├── OldCod/                   # Legacy files
├── package-lock.json         # Lock file for dependencies
├── package.json              # Project dependencies and scripts
├── public/                   # Static assets
├── README.md                 # Project documentation
├── scripts/                  # Deployment and utility scripts
├── src/                      # React frontend
├── test/                     # Smart contract tests
└── .gitignore                # Git ignore file
📧 Technologies Used
Solidity: For smart contract development.
Hardhat: For deploying and testing contracts.
React: Frontend for DEX interaction.
JavaScript: For dynamic frontend features and testing.
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
Run frontend:

bash
Copy
Edit
npm start
The app will be available at http://localhost:3000.

🔗 Connect with Me
GitHub: BladeCMD
Twitter: @
TikTok: @
