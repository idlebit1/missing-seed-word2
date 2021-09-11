# missing-seed-word2
Given 11 seed words and a tezos address, find the missing word and its position

MIT License

This script assumes your Tezos address was created for an HD Wallet with default derivation path. This is what Temple Wallet and Kukai do by default out of the box. 

# Clone this repo

```
git clone https://github.com/idlebit1/missing-seed-word2.git
```

# Clone and install `py_crypto_hd_wallet`

(Make sure you are use Pip 3)

```
git clone https://github.com/ebellocchia/py_crypto_hd_wallet.git
cd py_crypto_hd_wallet
pip install py_crypto_hd_wallet
cd ..
```

# Run script and input 11 words and tezos address

The script will prompt you to put in your eleven words. Then it will prompt you to put in your tezos address. Then, if it finds a matching 12 word seed phrase, it will print it out.

This should finish in a few dozen seconds, or maybe a few minutes.

(Make sure you are running Python 3)

```
cd missing-seed-word2
python script.py
11 words> embody unlock top alley august three need alarm slow unfair globe
tezos address> tz1e5KvFAK4sqcFSHcuVaGtXxeR3BCZz47Ud
searching...
embody unlock top toy alley august three need alarm slow unfair globe
```
