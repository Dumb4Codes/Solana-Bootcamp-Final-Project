# NFT Basics 

## Program ID
**Program ID**: 72mDXcBHRB4Cde3oFnStNVMge4KjkVQuPZzdKE556yJo


## Functions

### Mint
Create a new NFT (Gem) for a video game, defining its color, rarity, and a short description. This function is akin to producing a unique digital collectible.

### Transfer
Send NFTs (Gems) from one player to another, facilitating the digital transfer of gems between player collections.

### Burn
Delete or destroy NFTs (Gems), essentially removing a digital gem from existence.

## Build and Deploy

### Build the Contract
1. Open a new terminal window.
2. Navigate to the program directory using the following command:
```
cd program
```
   
Paste and execute the following code in the terminal:
  ```
  cargo build-sbf
  ```

## Set up your config
Paste the following code in the terminal:
```
  solana config set --url devnet
```

## Get dev tokens
To deploy a contract, you need tokens. Obtain tokens by executing the following command in your terminal:
```
solana airdrop 1
```

You can check your token balance with the following command:
```
solana balance
```

## Deploy the Contract
Use the following command for deployment:
```
solana program deploy target/deploy/nft.so
```


## Additional Information
> Ensure that you have Solana installed and configured on your machine.
>> Make sure to replace the placeholder Program ID `(72mDXcBHRB4Cde3oFnStNVMge4KjkVQuPZzdKE556yJo)` with your actual Program ID.
>>> Customize the mint, transfer, and burn functions based on the specific requirements of your NFT project.
>>>> Include any additional information or instructions necessary for users to interact with your NFT contract on the Solana blockchain.
>>>>> Feel free to customize and elaborate on the instructions based on your specific project requirements and the intended audience for your GitHub repository.

