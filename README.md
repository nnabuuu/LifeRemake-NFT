# Life Remake NFT 

English / [中文](README_cn.md)

LifeRemake on-chain generative NFT is the pilot activity for LifeRemake GameFi. 

### About the NFT

The NFT randomly draws 1 - 3 talents from talent pool based on rarity. 

Total supply: 8800 (8640 to mint public + 160 to mint by the owner)

##### Talent rarity level and chance (in each draw):
```
Grade 0: 70 %
Grade 1: 27 %
Grade 2: 2.7 %
Grade 3: 0.3 %
```

### How to get 

1. The contact has implemented opensea interface so you can purchase / sell NFT on opensea.io 

2. `claim()` directly from contact, first 1000 are free to claim, the rest costs 0.01ETH each.

### Restrictions

The contract restricts that only 1 NFT gets minted in every block. 
    
This is because we use previous blockhash as pseudo-random seed for the token id. 

This avoids collisions in a certain degree but compromises randomness somehow. (Anyway we don't care about that in this scenario).

We will release source code for the contract once all tokens get minted.