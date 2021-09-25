MNEMONIC=""
INFURA_KEY=""

DEPLOYER_WALLET = ""
ADMIN_WALLET = ""

PRIVATE_KEY_OF_DEPLOYER_WALLET = ""
PRIVATE_KEY_OF_ADMIN_WALLET = ""


setup:

$ npm install
$ npm run compile:bsc-testnet
$ npm run test:nft-yield-farming_bsc-testnet
($ truffle test ./test/test-bsc/NFTYieldFarmingOnBSC.test.js --network bsc_testnet)
$ npm run script:nft-yield-farming_bsc-testnet
($ truffle exec ./scripts/script-bsc/NFTYieldFarmingOnBSC.script.js --network bsc_testnet)
