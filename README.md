# Jewel Oracle 
Welcome to the **Jewel Oracle** project. The Jewel Oracle project has been created to provide an oracle for baskets of assets which are compliant with ERC6551. 
## The Challenge
The challenge that exists today is that there is no easy way to collateralise a basket of assets. Typically as a user you have to value and secure each asset individually then acquire loans against each asset individually before your basket can function. From a scaling perspective this is highly inadequate in markets where prices fluctuate rapidly and assets are traded with high frequency.

## The Jewel in the Solution 
This is where the **Jewel Oracle** project comes in. It’s purpose is to provide an easy way by which an effective basket owner can forge an ERC6551 NFT and consequently get it’s true value based on the market price of it’s constituent parts. This opens up quite a few avenues for financial innovation as it sees the beginning on and off chain asset collateralization. However for all this to work the prices of the constituent parts need to be effectively tracked such that when the ERC6551 NFT is held as collateral, any constituent part price collapses or price surges are instantly reflected. This also changes the behaviour of liquidations from being carte blanche to becoming more sophisticated whereby various formulae can be used to reduce the impact of liquidation whilst at the same time managing the risk to lenders.

## Jewel Oracle Proof of Concept 
The proof of concept built by the Jewel Oracle project will demonstrate how ERC6551 NFTs can be effectively monitored and tracked, whilst ensuring that any on chain parties with an interest in the asset have full price visibility to any changes which may occur with the asset.
![enter image description here](https://github.com/cryptotwilight/jewel-oracle/blob/main/media/jewel-Page-3.drawio.png?raw=true)
  

The Jewel Oracle project will also look to illuminate the major risks and where possible provide mitigation strategies for the major risks associated with ERC6551 NFTs namely those of disassembly and constituent part volatility. There are more subtle risks such as those of rehypothecation which can lead to systemic contagion however these will look to be explored in further iterations of the Jewel Oracle project.
## Road to Implementation
The Jewel Oracle PoC will broadly follow the strawman architecture described below: 
![enter image description here](https://github.com/cryptotwilight/jewel-oracle/blob/main/media/jewel-Jewel%20Oracle%20PoC%20strawman.drawio.png?raw=true)

### Build Phases 
The Jewel Oracle PoC will consist initially of the following build phases:

 - Onchain Data Acquisition 
 - Onchain Data Cleansing & Normalisation
 - Onchain Data Aggregation 
 - Onchain Onward Data Distribution 

The goal will be for each phase to have a documented discovery period followed by build iterations to create on chain services that have minimal off chain reliance. 

