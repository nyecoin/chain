# chain

1. Shut Down the Wallet
2. Make Backup of the data directory and also copy the wallet.dat outside
3. Delete the exisitng Data directory
4. Paste the New Data directory (from  https://we.tl/t-10lXR5Y690  please replace full) and replace the wallet.dat file.
5. Now rescan and reindex the chain using -reindex and -rescan flag
(for this setp you will need to opend the cmd at the location where nyecoin-qt is located and then run nyecoin-qt.exe -reindex and -rescan)
or (nyecoind -reindex -rescan)
It will take a while
6. Once done, you will see your balances and all
7. In case of anything drastic you can  go back to the backup copy of your datadirectory following same set of steps 
