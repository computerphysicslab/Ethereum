## LydianElectrum

Ethereum fork on Golang to deploy a stablecoin native crytocurrency fully Smart Contract driven

Motto: "When 1000000000000000000 weis is 1 euro".


### Intro, what it is LydianElectrum?
	
LydianElectrum is an Ethereum code fork that allows a ledger-native stablecoin to rule blockchain transactions.

Besides, LydianElectrum by default adds the standard feature of tokenizing the native stablecoin into an ERC-20 master contract.


### Ledger-Native vs Contract-Token

There are two ways to develop a new coin on Blockchain:

Ledger-Native: By building a new network having its own native coin and balances are stored on the ledger.

Contract-Token: By deploying token contracts that store and transfer user wallet’s token balances.

### Ledger-Native vs Contract-Token

LydianElectrum uses both strategies at the same time, getting the best from each one: 

Ledger-Native: Mining fees are paid on native currency, so miners will get stablecoins for their task.

Contract-Token: Every oracle centralized actions (mint/destroy) to keep the backed fiat in-sync will be regulated by an ERC-20 Smart Contract.

### Stablecoin CryptoEuro

LydianElectrum native coin is called CryptoEuro. It is a stablecoin backed 1:1 by Euro. The balance field has 18 decimals, so if your wallet has a balance of 1000000000000000000 you will be able to withdraw fiat for 1 euro into your bank account.


### Oracle mint/destroy process

In order to keep the 1:1 euro back for CryptoEuro, there is an oracle process to mint coins whenever fiat deposits are carried out.

Withdrawns trigger same process back to front, destroying user wallet’s coins.


### Miners’ fees and rewards

LydianElectrum gets consensus about new blocks by using the same PoW mechanism as Ethereum with one small difference: miners don’t receive rewards, just fees.

Rewards in Ethereum are inflationist incentives to optimze the miner process, but they are out of the scope for stablecoin blockchains such as LydianElectrum.

A stablecoin network backs every cryptocoin with a fiat counterpart deposited on a bank vault. So there is no chance to create new coins (rewards) out of nothing to incentivize mining process. 

By paying miners with fees, LydianElectrum guarantees every miner will receive a backed amount of CryptoEuros for his work, inmediatly tradable to fiat euros through an oracle withdraw.


## Contribution

Thank you for considering to help out with the source code! We welcome contributions
from anyone!

If you'd like to contribute to LydianElectrum, please check up with the core devs first on juan@marketpay.io
to ensure those changes are in line with the general philosophy of the project and/or get
some early feedback which can make both your efforts much lighter as well as our review
and merge procedures quick and simple.


## License

LydianElectrum is licensed under the
[GNU Lesser General Public License v3.0](https://www.gnu.org/licenses/lgpl-3.0.en.html),
also included in our repository in the `COPYING.LESSER` file.
