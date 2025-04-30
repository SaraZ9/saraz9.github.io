---
title: "BlockCrafters DApp"  
date: 2025-04-30  
lastmod: 2025-04-30  
Tags: ["Web3", "Solidity", "Smart Contracts", "Flutter", "IPFS", "Mobile App Development", "Ethereum", "Decentralized App", "Unit Testing"]  
author: ["Sara Zhang"]  
description: "BlockCrafters is a Web3 decentralized crowdfunding platform that enables startups to raise capital securely and transparently by issuing project-specific tokens. Built with a Flutter frontend and a modular smart contract backend, the platform supports milestone-based fund release, token-holder voting, and future governance extensions."  
summary: "A decentralized Web3 crowdfunding platform built with Solidity and Flutter, featuring on-chain governance, milestone-based fund release, and ERC20 token issuance per project."  
cover:  
    image: "blockcrafters_cover.png"  
    alt: "cover for the project"  
    relative: false  
editPost:  
    URL: "../"  
    Text: "view all projects"  
---

<div align="center">
    <img src="project8.png" alt="cover for the project" width="600"/>
</div>

### Project Overview  
**BlockCrafters** is a decentralized crowdfunding platform designed to address the limitations of traditional startup fundraising. Built on the Ethereum blockchain with a Flutter frontend, the platform allows startups to raise funds through project-specific ERC20 tokens that also serve as governance tools. Funds are released based on milestone progress and investor voting, ensuring transparency, accountability, and community trust.

### Key Features  
- **Tokenized Fundraising**: Each project issues a unique ERC20 token to represent ownership and enable milestone voting.  
- **Milestone-Based Fund Release**: Funds are held in smart contract escrow and only released upon reaching pre-set goals.  
- **Investor Governance**: Token holders vote on key project decisions, including milestone approval and deadline extensions.  
- **Cross-Platform Frontend**: Built with **Flutter**, the app supports both web and mobile users.  
- **Decentralized File Storage**: Leveraged **IPFS** for storing project metadata such as descriptions, images, and social links.  
- **Upgradeable Contracts**: Smart contract architecture supports future extensibility via OpenZeppelin’s upgradeable proxies.  

### Technical Details  
- **Smart Contracts** written in **Solidity**, handling project creation, milestone management, fund distribution, refunds, and governance.  
- **Frontend** developed with **Flutter**, integrating WalletConnect for Ethereum wallet access.  
- **File handling** powered by **IPFS** (via Pinata), used to store project descriptions and media in a decentralized way.  
- **State management** via Bloc pattern, supporting asynchronous interaction with the blockchain.  
- **WalletConnect** enables users to authenticate, invest, and vote using MetaMask or other EVM-compatible wallets.  
- **Unit Testing** conducted with **Hardhat** and **Chai** to ensure the integrity and security of core contract functionalities.  

### Links  
- [GitHub Repository](https://github.com/saraz9/blockcrafters-dapp)
- [Project Report](report.pdf)
- [Slide Deck](slides.pdf)
---