https://web3py.readthedocs.io/en/stable/

Infura as a EVM Client

- $ pip3 install web3
- $ npm intall web3

node console

var Web3 = require('web3')
Web3

var url = 'https://ropsten.infura.io/v3/9d5ba8b3d1ab4df8a4701746faf22e2c'
var web3 = new Web3(url)
web3

var address = '0x70c4d4DE5B6071D087AF3288b7C0951e19cBb26D';

web3.eth.getBalance(address, (err, bal) => {
    balance = bal
    });
web3.eth.utils.fromWei(balance, 'ether')
balance
