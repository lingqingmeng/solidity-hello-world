# solidity-hello-world

## Prereqs
Tested on OSX Sierra 10.12.xxx and Ubuntu 16.04
### Node 8.5
On Ubuntu
```
curl -sL https://deb.nodesource.com/setup_8.x | sudo -E bash -
sudo apt-get install -y nodejs
```

Or on Mac go to https://nodejs.org/en/download/current/ and download
the Macintosh Installer (node-v8.5.0.pkg)

### TestRPC
Attach to test blockchain, seperate shell needed. 
```
sudo npm install -g ethereumjs-testrpc
testrpc
```


## Install
```
npm install 
npm start
```

If you're getting `Error: Invalid JSON RPC response: undefined` you didn't follow step 2 of prerequisites, testrpc when running should display.

```
Available Accounts
==================
(0) 0x6dfd494e8aebb26e580d24cf8e87ff93425c65f4
(1) 0xa8a6498f2ea1d42d76d9705336b117af8e35dc07
(2) 0x57c9d4c9dbb218bc7eda305683c5da5697a858ed
(3) 0xe1957b57bb49f539fcf5bc65afc392f7c843443d
(4) 0x5815d2eb576084f8a58cee00ff02ef6ade7d0b30
(5) 0xa0d80c8c4d0f498e75dbea68f59e08520ef7538a
(6) 0x8b9a1bf90e4ee787b084435d8530415046f1e64d
(7) 0xc1425d85ee1789e016fedfd9abb2535aeacefa93
(8) 0xecac6797d6069d3667e513cf8f47a354ff5116d0
(9) 0x2f56536586b3484b980fecb42fa1ca4e08926ff4

Private Keys
==================
(0) 93974e68c58e0a2829c2bca712429be87566554384cf58d961193d2664c83e69
(1) a43dd930e9f34d6f40d5e283a0b8d010bc25a3b86f1dbc5147e889be52e7d058
(2) 0dbef90621032ed98048822387cad34df6ef8587b166d0a63878ac9d6669dd61
(3) 1056fb1ef104ed94a5e92f677bd0a110ab8d3375577a5a7fb583549288cdcb52
(4) 412652d60bee01561e6dd913780862c379fcc7eb2557ba8f48b01183d8b5808f
(5) 5fc73263a9197674ce9e75cfd3a833cb23f98e724534d9dd769442a145d92e6b
(6) 9b598b89956795d8f9b33f292f6386aa3282b5f5bfcc536607dff224122d2cda
(7) 1ded4a96ecaad6f1e3754e3d57afc842e3bf0c9c15383e5acb8ecbd9e56cafdc
(8) 1b02f59bfa88e43cb96dddea15311f6949933bc3b1c3865e722e91f052d92f37
(9) 73d70eb679200418d4b5999d622c837ec6c66287b8b307e0830629cb0b1faaea

HD Wallet
==================
Mnemonic:      sail skill drum window pact kidney foot rigid owner royal seminar magic
Base HD Path:  m/44'/60'/0'/0/{account_index}

Listening on localhost:8545
```