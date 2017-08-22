# setGetUpdate
Uses InterPlanetaryFileSystem and Ethereum to never be denied package updates/files.

# Background
This shell script allows someone to take a ipfs hash from a file they uploaded to ipfs and put that ipfs hash on the ethereum blockchain.
By leverging ipfs your update package/file is now stored on multiple computers and not a centralized server that can be brought down.
Then we can put that hash on the Ethereum blockchain and now the hash is always avaible if you know the contract address or transaction hashes.
We can also take the contract address of the first upload and then update that contract with more ipfs hashes. 

# Install
For the script to run succesfully all you need is to have ipfs running on your system and you must be fully synced to a ethereum network of your choice.
When creating a new contract to submitt to the blockchain make sure your ether account you are using is unlocked and that the echo.sol contract is in the same directory as the script.

# Note
Options 4 & 5 do not currently work, they will be fixed/added in future updates.
Any feedback about the script is greatly appericated and welcomed.
