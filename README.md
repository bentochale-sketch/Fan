# Fan
🏆 Winning Auction Contract 

This repository contains a **Clarity smart contract** that enables a **transparent, fair, and trustless auction system** for awarding a contract on Web3.  
It is fully compatible with **Clarinet**, making it easy to test, debug, and extend.

 🎯 Purpose

The goal of this smart contract is to:
- Allow participants to **bid in STX** for a contract or opportunity.  
- Guarantee that the **highest valid bidder wins** once the auction ends.  
- Ensure that **non-winning bidders** can safely withdraw their funds.  
- Empower the contract **owner** to finalize and claim the winning funds.  

This setup models **real-world contract awards** in a decentralized, auditable, and secure way.

🚀 Features

- **Initialization**
  - Owner sets: auction title, minimum bid, start block, end block.  
- **Bidding**
  - Anyone can place a bid higher than the current highest.  
  - Bids are locked in STX as escrow until the auction ends.  
- **Withdrawals**
  - Losing bidders can reclaim their STX after being outbid.  
- **Finalization**
  - Once the auction ends, the contract is finalized and the winning STX is released to the owner.  



