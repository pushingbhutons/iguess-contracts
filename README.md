<a href="https://iguess.zeemz.xyz"><img src="https://raw.githubusercontent.com/pushingbhutons/iguess-contracts/master/logo_512.png" height="70"></a>

# iguess-contracts

iGuess, is a number guessing game where the user bets that the wheel will land on a number between 1 and their guess (a number between 6 and 96). The game is currently set for Ethereum play, ZMZB and ZMZLR coming soon.  

Formerly, [Wheelspin](https://wheelspin.io) is a luck game, similar to Wheel of Fortune, built in Solidity and deployed in Ethereum [Mainnet](https://blockscout.com/eth/mainnet/).

## Wheelspin Contract Addresses

- [mainnet](https://etherscan.io/address/0xf17b52226d78070696ff2dddcb08bb65986054e1): 0xf17b52226d78070696ff2dddcb08bb65986054e1

- [ropsten](https://ropsten.etherscan.io/address/0x71ff026f519c8aabf9eddde75946701dd83de63c): 0x71ff026f519c8aabf9eddde75946701dd83de63c

## Requirements

You will need a web browser and an Ethereum wallet browser extension such as [Metamask](https://metamask.io/).

## How to play

- deposit some Ether in the contract

- select the stake and a number X

- click spin to play your bet

- if the wheel rolls a number between 1 and your number X you will win a prize

## Limits

[From the code](https://github.com/pushingbhutons/iguess-contracts/blob/master/Gamble.sol#L12):

```
    uint public constant MIN_DEPOSIT = 0.1 ether;
    uint public constant MAX_ROLL_UNDER = 96;
    uint public constant MIN_ROLL_UNDER = 6;
    uint public minBet = 0.05 ether;
    uint public maxBet = 1 ether;
```

## Disclaimer

- Play at your own risk. Lost bets or technical issues might result in financial loss.

## License

Code released under the [MIT license](./LICENSE).
