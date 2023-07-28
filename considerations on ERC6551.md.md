# Considerations on ERC6551
## Introduction 
The following paper has been prepared to discuss some of the considerations that need to be thought around when looking to implement price tracking on an ERC6551 compliant NFT. The objective is to provide a consistently accurate price on the NFT at an optimal **gas fee**. 

There are several considerations that need to be borne in mind when looking to provide an oracle they are:

 1. NFT account composition 
 2. NFT account transience 
 3. NFT account registration 

## NFT account Composition
NFT account composition is the most important consideration as with ERC6551 an NFT gains the same abilities as those for a normal account. Therefore the account can have a mix of assets some of which are of a type that can be priced. The primary consideration here is the ability to search and identify assets in the account efficiently on chain. 

## NFT account Transience
NFT account transience is a consideration as the NFT owner can change the composition of the account at any time. This presents an issue when the account is being used e.g. traded. Also ERC6551 makes no mention as to the recommended behaviour in the event of the owning NFT being burnt. 

## NFT account Registration 
An NFT can be registered for an NFT account across multiple ERC6551 compliant registries on the same chain. Each account for the NFT issued by a given registry will have a different composition. Hence when determining the value of the NFT, the address of the registry that issued the account is required. 
