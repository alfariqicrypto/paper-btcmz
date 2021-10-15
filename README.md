
**Paper Wallet Bitcoin Mono Generator**

Just drop the files in a publicly accessible web folder and you've got your own copy of the explorer.

# BitcoinMono BTCMZ
## How to fork for your own coin
Edit the values in index.html on lines 28, 31, 47, 66, 87, 90  to your coin  
Edit the value on line 1626 in crypto_utils.js, address prefix to your address prefix, and your coin info  
Replace logo.png with your logo, and that is it!

Example :

var config = {
coinUnitPlaces: 12,
coinSymbol: 'BTCMZ',
coinName: 'BitcoinMono',
coinUriPrefix: 'bitcoinmono:',
addressPrefix: 3771344
 
With AddressPrefix use CRYPTONOTE_PUBLIC_ADDRESS_BASE58_PREFIX = 3771344; // btcm) 

https://github.com/uaicoin/uaicoin/issues/2

https://cryptonotestarter.org/create-wallet.html

## LICENSE

This Project is licensed under AGPL v3.0.
```
// Copyright (c) 2018, The TurtleCoin Developers
// Copyright (c) 2018-2021, The DeroGold Association
// Copyright (c) 2021, Alfariqi Crypto
```
