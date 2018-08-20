# scatter-integrate-demo

## EOS DApp integrate with Scatter



This is a very simple Demo project to show that how to sign a EOS transaction with Scatter.


## Env:
	Scatter Classic: 	6.1.7       https://github.com/GetScatter/ScatterWebExtension
	scatter-js:         2.4         https://github.com/GetScatter/scatter-js
	Scatter Desktop:    v8.6.0      https://github.com/GetScatter/ScatterDesktop/releases
	EOS:                1.1.1
	"eosjs":            "^16.0.0",  https://github.com/eosio/eosjs
    "eosjs-api":        "^6.3.2",
    "eosjs-ecc":        "^4.0.2",


## Pre-requirements:

### 1. EOS node should start up with HTTP and Wallet plugin

	plugin = eosio::wallet_api_plugin
	plugin = eosio::chain_api_plugin
	plugin = eosio::http_plugin

### 2. You should config EOS node server Access-Control-Allow-Origin in config.ini file
	
	access-control-allow-origin = *

### 3. You should deploy the contract "eosio.token"

### 4. Here is my EOS node server
	39.105.91.238:8888

### 5. And demo account info
	account :	 letsgoletsgo
	private key: 5JyMMNXdeky8DeQCQRkgfMBcAJ2kAme1Xvfs89ZZC1NX5jwBV3B


## FAQ
### Q: How do i get eosjs file?
    According to the EOSJS github readme file,https://github.com/EOSIO/eosjs/blob/master/README.md, we can use below commands to generate it.
    
    git clone https://github.com/EOSIO/eosjs.git
    cd eosjs
    npm install
    npm run build_browser
    # builds: ./dist/eos.js load with ./dist/index.html
    
## Welcome to visit our EOS DApp game <a href="http://www.pandafun.io">PandaFun</a>
    
    Panda Fun is the first real-time tactics blockchain dApp game based on EOS in the world! 
    It combines all the exciting features of Monopoly except you'll be able to also train
    and update your avatars to gain specifc skills. 
    
    All the important codes concerning game fairnress are fully open-source and on chain so
    that you'll know you're not being fooled by "the dealer". Equally important, there is NO
    PRE-SALE of tokens in any kind. Our own team has been the SOLE source of funding and 
    technology behind the game because we believe this way we'd retain the very philosophy 
    of blockchain. 

    As soon as the EOS mainnet launches, we will STOP giving away our free pandas. 

    So please go to our website and get your free pandas:  pandafun.io 

Also, you are highly welcome to your telegram group: https://t.me/joinchat/JFW0FE8OBoL6_eyOyar02A


