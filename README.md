# Starter kit for smart contracts developing

### How to install and use

To set up the repository, run the below

```bash

git clone https://github.com/AnastasiaMenshikova/starter-kit

cd starter-kit

yarn install

yarn start

```
Create the `.env` file and add your own API keys and private key by using `.example.env`. 

To deploy smart contract to testnet use:

 ```bash
 
 yarn deploy --network <NETWORK-NAME>

 ```

For testing added static analyzer [Slither](https://github.com/crytic/slither) for Solidity code. Run following command:

```bash

yarn slither

```
If you want to write unit tests for your solidity code and check coverage of tests, run command:

```bash

yarn coverage

```