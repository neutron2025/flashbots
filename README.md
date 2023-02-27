```shell
mkdir flashbots
cd flashbots
npm init --yes
npm install --save-dev hardhat @nomicfoundation/hardhat-toolbox


npx hardhat  选择 Create a Javascript Project

npm install @flashbots/ethers-provider-bundle @openzeppelin/contracts dotenv

在contract 目录下创建FakeNFT.sol

修改 hardhat.config.js 文件
创建.env文件并配置 
QUICKNODE_RPC_URL="QUICKNODE_RPC_URL"
PRIVATE_KEY="YOUR-PRIVATE-KEY"
QUICKNODE_WS_URL="QUICKNODE_WS_URL"

在scripts目录下创建 flashbots.js

部署 npx hardhat run scripts/flashbots.js --network goerli


```