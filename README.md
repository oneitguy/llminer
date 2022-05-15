
# Bitcoin Private Key Miner for the Keymaker 3X Pool
##(New update is in the works.)
This software will  attempt to create a bitcoin address collision. If a key is found the key will be reported to the pool. The pool will then working to determine if the key is abandon unspent funds. Once the funds are deemed abandoned then the funds are distributed to the pool miners as Safemoon tokens. 

 

# Install

You can run llminer in Windows or Linux. In order to run using Linux you have to download dotnet core 5.0.  
    
## For Linux or Windows

    $ wget https://github.com/oneitguy/llminer/releases/download/latest/llminer.tar
    $ tar -xf llminer.tar
    $ dotnet llminer.dll
    
## For Linux GPU

    You will need to compile the following applications, delete the .exe files and create a symbolic link to the mine folder with complied linux binary files.
    
    BitCrack - https://github.com/brichard19/BitCrack/releases
    LOLMiner - https://github.com/Lolliedieb/lolMiner-releases/releases
    xmrig - https://github.com/xmrig/xmrig/releases/tag/v6.16.2
    
    symbolic link example
    ln -s [Source_File_Path] [Symbolic_Link_Path]

# Configure

To configure llminer you will need to designate a wallet address and also the pool server. If the address.worker are already in use you will need to 
Example

    "worker": "0xcE3b27807B13f1c6... 82C7094C.worker1",
    "uid": "E02E9B2A148...D",
    "GPU_pool": "https://keymaker.cc/gpool"

 

##  Whitelist

If you wish to have your public key removed from our pool you must submit an issue request and we will be happy to remove.   




