# blind-sig-js
Interact with cashu mints in vanilla javascript

# How to try it
Just click here: https://supertestnet.github.io/blind-sig-js/

# What it is
This page contains working code for interacting with a cashu server in the browser and doing the following transactions:
- A pair of regular transactions that create some ecash and redeem it
- A pair of p2pk transactions that lock some ecash to a pubkey and then sign to redeem it
- A pair of p2pk sighash_all transactions that do the same thing except they also require whoever redeems it to sign the outputs of the transaction
- A pair of multisig transactions that lock some ecash to a multisig and then use multiple signatures to redeem it

# Acknowledgements
All I did was take [this code](https://github.com/gandlafbtc/cashu-crypto-js) written by Gandlaf BTC and ran it through webpack to make it work in the browser, then nag Calle til he helped me debug why my test transactions weren't working

So all thanks should be directed to them
