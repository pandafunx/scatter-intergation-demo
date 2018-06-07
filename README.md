# scatter-intergation-demo
EOS DApp integrate with Scatter



This is a very simple Demo project to show that how to sign a EOS transaction with Scatter.


Env:
	Scatter: 	4.0+
	EOS Dawn: 	4.2
	EOSJS:  	13.x.x  For version info : https://github.com/EOSIO/eosjs


Pre-requires:

1. EOS node should start up with HTTP and Wallet plugin

	plugin = eosio::wallet_api_plugin
	plugin = eosio::chain_api_plugin
	plugin = eosio::http_plugin

2. You should config EOS node server Access-Control-Allow-Origin in config.ini file
	
	access-control-allow-origin = *

3. You should deploy the contract "eosio.token"

4. Here is my EOS node server : 
	39.105.91.238:8888

5. And demo account info :
	account :	 letsgoletsgo
	private key: 5JyMMNXdeky8DeQCQRkgfMBcAJ2kAme1Xvfs89ZZC1NX5jwBV3B


Welcome to visit our EOS DApp Game: http://pandafun.io 
