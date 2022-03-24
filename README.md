# raywom
Creating personal cryptocurrency with rust smart contracts using Anchor

##  important files: 
programs/rust_token_js/src/lib.rs

tests/rust_token_js.js

# Steps:

1. setup Solana id
```
solana config set --url localhost
solana-keygen new -o $HOME/.config/solana/id.json
```

2. Project build:

`anchor build`

3. Test project:

`npm install mocha`

`anchor test`

output:
```
rust_token_js
    ✔ Initializes test state (1318ms)
    ✔ Mints a token (415ms)
    ✔ Transfers a token (416ms)
    ✔ Burns a token (398ms)
    ✔ Set new mint authority (410ms)


  5 passing (3s)

Done in 8.57s.
```
