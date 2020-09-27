## Note: A fork of geth optimized for mempool analysis - WIP

Changes: 
* Increasing the local mempool size (default is 4096 + 1024) to access/store as many mempool tx's as possible
* Editing the backend API to return other information such as time a tx was first seen
* Pipe mempool data into a different database to access/store all the tx later
* ???

End goal is to analyze the mempool for MEV and gas bids b/w frontrunning/arbitrage bots. 


go-ethereum's [README](https://github.com/ethereum/go-ethereum/blob/master/README.md)
