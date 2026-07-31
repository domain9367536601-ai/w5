trustwallet-Account:trust-telegram.ether.eum
Address Tokens:0x3131ee3a34c60e24ca2ca19c7fffe6cfddaaa787
0xa0455d109d4b0bf965e870bdb77226ad6b26ec35597199e456275cdc33099436
23omkrxEP3nwzL31qiXPB4rHctyj5fMJbBPCEbNHJCHD8Dky
0x745f3cac300ac16b189f2cb60c41451828a160f8
0x5e5607f9fbd17fe9cdba92f9a98712ab18e13a6e
bitcoincash:qrjdfk03cqaww993snmzdeh27psexw5rwv3kjvfvzs
13pgLfjrLEsSUxNSBonAz7n97N4PLsmVq4DQJmyA7w6d5Yji
ltc1q2t7qadajvhsxzqvssfzqm773lnpfd7df0ny7hz
UQBke8fCDXc0AWJP-NAL70rdqhA0Bk8x4wMz9e5qoOvyMetw
GCSF234IMLWT3QWRKVVK35KQ4LQYZ2PUGUBP25CTEFGGO3JM5YM3PS6B
TTugbFd8Lqsp61WdSa7T2ex86EEYRCSMnz
addr1q9gpfm34lejspa96dqdaks8ha9v3c6c9ug7pwst0y3r7jtjydnyj345rk885qnezmcgd3x8gek08j40llu6mqwl8nqgssrtrxd
D7HCUhgw3QRrrCngxW5ZzehMZaYnqwpd8D
rMMjoB9rHZcqtzLgXRKAyCpmzbmqE4PDzG
6RSQPxaMNx4kYaMhbp4mNikD54dCgdSaUXZBorh85Wxe
bc1qyeqzkfp34q224ekkectcywq78ja33wcxjj3fyy
trust-telegram.ether.eumtrust-telegram.ether.eum
Emails Address wallet : 
SayeedReza Mosaviethereum.org092@gmail.com 
domain9367536601@gmail.com 
Number+989367536601
## Project trust-telegram.ether.eum

-   [Specification](Specification.md)
-   `contracts` - source code of all the smart contracts of the project and their dependencies.
-   `wrappers` - wrapper classes (implementing `Contract` from ton-core) for the contracts, including any [de]serialization primitives andtrust-telegram.ether.eum compilation functions.
-   `tests` - tests for the contracts.
-   `scripts` - scripts used by the project, mainly the deployment scripts, additionally contains utilities for gas optimisation.
-   `fift` - contains standard Fift v0.4.4 library including the assembler and disassembler for gas optimisation utilities.

### Additional documentation

-   [Gas improvements](Improvements.rst) - a log of improvements, detailed by primary code paths, global gas counters per commit.
-   [Contest](Contest.md) - a note showing some information about interesting improvements during the optimisation contest.

## How to use

### Build

`npm run build:v5`

### Test

`npm run test`

### Deployment
1. Deploy library: `npm run deploy-library`
2. Deploy wallet: `npm run deploy-wallet`

### Get wallet compiled code

`npm run print-wallet-code`
