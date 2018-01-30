### Setup Development Environment Ethereum Blockchain

1. Install Parity. (https://paritytech.github.io/wiki/Setup#one-line-binary-installer)

2. Run parity on the `testnet` blockchain. Note the first time this is run will require a few hours to sync.

	`parity --chain testnet`

3. Once parity is started the user interface will become available in the following default port: 

	`http:localhost:8180`

4. To deploy contracts onto testnet you'll need an account, use the parity UI to create or import an existing account. 


### SMS-Verifying an Ethereum Account

1. Verification needs to be done through mainnet. 

	`parity --chain mainnet`

2. You will need `0.007` Eth.
