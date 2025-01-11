# BlocHome: Smart Contract Real Estate Application

BlocHome is a blockchain-based platform revolutionizing the real estate market by providing secure, efficient, and transparent services for property sales, rentals, and real estate launches. It utilizes smart contracts and digital tokens to streamline real estate management, enabling investors, property owners, and tenants to maximize their assets.

---

## Key Features

### Property Management
- **Property Listing Management**: Simplified listings for luxury homes, apartments, and investment properties.
- **Auctions**: Conduct secure, transparent property auctions.
- **Token Management**: Efficient distribution and management of digital tokens.
- **Smart Contracts**:
  - Lease/Rental Agreements
  - Seller/Buyer and Owner/Tenant Contracts
  - Security Deposits
- **Online Web Portal**: User-friendly interface for property management.

### Financial Transaction Management
- **Blockchain Technology**: Enhances transparency, reduces intermediaries, and supports fractional ownership.
- **Digital Wallet Integration**: Includes MetaMask for secure asset storage and transaction facilitation.
- **Ethereum Gas Mechanism**: Optimized transaction execution and smart contract deployment.
- **Smart Contracts**: Self-executing contracts ensuring traceable and irreversible transactions.
- **Digital Tokens (NFTs)**: Enables property tokenization using ERC721 and ERCX standards for trading, renting, and mortgage functions.

---

## Development Platforms
- **[InterPlanetary File System (IPFS)](https://pinata.cloud/)**: Decentralized file storage and sharing.
- **[MetaMask](https://metamask.io/)**: Browser plugin for Ethereum transactions.
- **[Web3.py](https://github.com/ethereum/web3.py)**: Python library for Ethereum blockchain integration.
- **Solidity**: Smart contract development.
- **Ganache**: Blockchain simulation for local testing.
- **Remix**: Ethereum IDE for smart contract deployment.

---

## Machine Learning Integration
BlocHome leverages machine learning models for housing market analysis, offering insights into property pricing and valuation:
- **Cluster Analysis**: Identifies price/sqft and sales price clusters.
- **Regression Models**: Predicts property sales prices and pricing per sqft.
- **Deep Learning Models**: Advanced predictions for property pricing.
- **Dataset**: AMES, Iowa Assessor's Home Sales (2006–2010).

---

## Regenerative Finance (ReFi) Applications
### Proposed Solutions
1. **Carbon Credit Marketplace**:
   - Tokenize carbon credits as NFTs for transparent trading.
   - Offset carbon footprints through verified green projects.
2. **Biodiversity Tokenization**:
   - Fund conservation efforts using tokenized incentives.
   - Promote ecosystem preservation with direct community engagement.

### Architecture Highlights
- **Carbon Credit Marketplace**: Blockchain network with users, credit issuers, and marketplaces.
- **Biodiversity Tokenization**: Sponsors, token systems, and conservation projects.

---

## Demo

Explore the BlocHome platform [here](https://maitree7.github.io/BlocHome_DeFi/).  
Role-based access available for:
- Admins (Property Listing)
- Owners/Leasors
- Tenants/Leasees

---

## Research and References
- [ERC721 Standard](https://eips.ethereum.org/EIPS/eip-721)
- [ERCX - EIP 2615](https://github.com/kohshiba/ERC-X)
- [MetaMask Documentation](https://metamask.io/)
- [Web3.py Documentation](https://github.com/ethereum/web3.py)

---

## Estimated Costs
Development, marketing, and operational costs are distributed as follows:
- **Development**: Blockchain integration, smart contract development, and user interface design.
- **Marketing & Outreach**: Target campaigns for environmentalists, investors, and real estate markets.
- **Operations**: Platform maintenance, customer support, and updates.

---

## Unique Selling Proposition (USP)
- **Transparency**: Blockchain ensures traceable and secure transactions.
- **Innovation**: Integrates smart contracts and tokenization for real estate operations.
- **Sustainability**: Supports regenerative finance models for environmental impac





...............................................

#### Housing Model Analysis - Machine Learning Model
---
Trains Models to to identify, categorize and value Housing Sales Price per sqft and Price. 
    
* **Data Highlights - AMES, IOWA Assessor's Home Sales(2006 - 2010)**
      
     * 2930 Rows * 82 columns (23 nominal, 23 ordinal, 14 discrete, and 20 continuous variables)
     * Nominal Variables : Identifies the type of dwelling involved in the sale and zoning classification
     * Ordinal: General shape of property and type of utilities
     * Discrete: Original construction dates
     * Continuous: Masonry veneer area in square feet

* **Cluster Analysis (K = Number of Clusters in the dataset = 7)**
      
     * Sale Price by Price / Sqft by Cluster
     
    <img src="./frontend/img/cluster.png" width="500"/><img src="./frontend/img/cluster_profile.png" width="500"/>
    
* **Regression Model to Predict - Sales Price** 
    
    Sales Price
    <img src="./frontend/img/reg_model_sp.png" width="500"/>
    
    Sale Price per Sqft
    <img src="./frontend/img/reg_model_sqft.png" width="500"/>
    
* **Deep Learning Model - Predict Sales Price**

    Sales Price
    <img src="./frontend/img/dl_sp.png" width="500"/>
    
    Sale Price per Sqft
    <img src="./frontend/img/dl_spft.png" width="500"/>

* **Model Comparison / Model Selection**

![model_cmp](./frontend/img/model_cmp.png)

















    
    

      
      








     

      
    
            











