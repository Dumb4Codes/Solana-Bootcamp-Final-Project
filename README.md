NFT_Basics
Program ID
Program ID : 72mDXcBHRB4Cde3oFnStNVMge4KjkVQuPZzdKE556yJo

Functions
Mint: Creating a new NFT (Gem) for a video game. We define its color, rarity, and a short description. Think of it as producing a unique digital collectible.
Transfer: Sending NFTs (Gems) from one player to another. Like passing a digital gem from one player's collection to another.
Burn: Deleting or destroying NFTs (Gems). It's like removing a digital gem from existence.
Build and Deploy
Build the contract
Open a new terminal window.
Enter "cd program" command in the terminal.
Then paste the following code in the terminal.
cargo build-sbf
Set up your config
Paste the following code in the terminal.
solana config set --url devnet
Get dev tokens
To deploy a contract, you need tokens. Get tokens by pasting the following command in your terminal.
solana airdrop 1 
You can check your balance by using the following command.
solana balance
Deploy the Contract
Use the following command for deployment.
solana program deploy target/deploy/nft.so 
