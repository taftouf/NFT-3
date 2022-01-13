# NFT Project


### Storage constants and variables
<ul>
  <li>Supply: The maximum number of NFTs that can be minted in your collection.</li>
  <li>Price: The amount of ether required to buy 1 NFT.</li>
  <li>Maximum number of mints per transaction: The upper limit of NFTs that you can mint at once.</li>
  <li>Base Token URI: The IPFS URL of the folder containing the JSON metadata.</li>
</ul>

### Constructor
 
I call the parent constructor and I set the name and symbol for our NFT collection.
And A set the baseTokenURI in my constructor call.

### Reserve NFTs function

this function is for reserve a few NFTs of the collection.

### Setting Base Token URI

This function tell the contract that the baseTokenURI variable that we defined is the base URI that the contract must use. 

### Mint function

this functions is for purchase and mint NFTs from my collection.

### Getting all tokens owned by a particular account

that function is returns all IDs owned by a particular holder. 

### Withdraw balance function

this function is for withdraw the ether that has been sent to the contract.

---

### Deploying the contract to Rinkeby

---

## Verifying my contract on Etherscan

- [etherscan](https://rinkeby.etherscan.io/address/0x1a418a2a2459AC287BB1D2fAD2f536585Cc96b9D)

## Viewing my NFTs on OpenSea

- [OpenSea Testnet](https://testnets.opensea.io/collection/nft-maarouf-nl6s4rhqoz)
