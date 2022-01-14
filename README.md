# NFT Project

NFT (non-fungible token) is a fascinating new technology that represents ownership of an asset digitally.

## contract explain

### Storage constants and variables
<ul>
  <li><b>Supply:</b> The maximum number of NFTs that can be minted in the collection.</li>
  <li><b>Price:</b> The amount of ether required to buy 1 NFT.</li>
  <li><b>Maximum number of mints per transaction:</b> The upper limit of NFTs that can mint at once.</li>
  <li><b>Base Token URI:</b> The IPFS URL of the folder containing the JSON metadata.</li>
</ul>

### Constructor
 
I call the parent constructor and I set the name and symbol for our NFT collection.
And I set the baseTokenURI in The constructor call.

### Reserve NFTs function

this function is for reserve a few NFTs of the collection.

### Setting Base Token URI

This function tell the contract that the baseTokenURI variable that I defined is the base URI that the contract must use. 

### Mint function

  this functions is for purchase and mint NFTs from the collection.

### Getting all tokens owned by a particular account
 

### Withdraw balance function

this function is for withdraw the ether that has been sent to the contract.

---

## Deploying the contract to Rinkeby



### Verifying my contract on Etherscan

- [etherscan](https://rinkeby.etherscan.io/address/0x1a418a2a2459AC287BB1D2fAD2f536585Cc96b9D)

### Viewing my NFTs on OpenSea

- [OpenSea Testnet](https://testnets.opensea.io/collection/nft-maarouf-nl6s4rhqoz)
