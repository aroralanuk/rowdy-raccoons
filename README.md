# Rowdy Raccoons

Blockchain at San Diego is planning to launch merch for our members,
patreons, partners, and alums. Kicker, it's a also an NFT collection.
PLanning an 150 piece collection with distribution:

- 3x5 for BAF, Encode, Basement
- 15 for Internal Team
- 20 for people with POAP or regular attendees
- 100 for sale at 0.1 ETH mint price for people who want to buy

User experience flow:

- We invite people to our frontend where they put in their details like wallet
  address, discord name, email, jersey size, nickname, number, etc till a
  specified deadline
- after the deadline, we airdrop the NFTs to the wallet using a merkle drop to
  the wallets which registered, store as the metadata the nickname and number,
  everything else on firebase. basd pays the fees, deployed on polygon or arbitrum
- put in the merch order
- after the presale, open to a public mint where user pay for gas and get their
  orders one-by-one. Use the funds to compensate the artists and fund the basd
  gnosis wallet.

Resources for smart contract + frontend work:

- [scaffold-eth](https://github.com/scaffold-eth/scaffold-eth-examples/tree/merkler)
- [anish's merkle airdrop](https://github.com/Anish-Agnihotri/merkle-airdrop-starter)
- [openzeppelin workshop](https://blog.openzeppelin.com/workshop-recap-building-an-nft-merkle-drop/)
- [foundry for testing](https://github.com/foundry-rs/foundry)
