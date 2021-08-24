# TraceLAbs

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```



### Task

Application should  allow a user to view transaction data from the Ethereum blockchain associated with a specific wallet address W that the user inputs, starting with block B. The application should get information on:

    wallets (addresses) and 

    amounts of ETH associated with transactions made to and from the given wallet W and

    show them in a simple human-readable way (ideally, through a web page). 

The application should collect and display ALL transaction data starting from the given block B. 

### Example: 

If a user requests to view transactions associated with the address 0xaa7a9ca87d3694b5755f213b5d04094b8d0f0a6f from block 9000000 to the current block, your application should be able to crawl and visualize all transaction data (addresses that have sent and received tokens from the address 0xaa7a9ca87d3694b5755f213b5d04094b8d0f0a6f , and how much ETH was used for a given transaction) in that period of time.

### For bonus points:

    Given a date in YYYY-MM-DD format, the program should return the exact value of ETH that was available on the given address at YYYY-MM-DD 00:00 UTC time.

    Do the same task above to include tokens amounts (other than ETH)

### External API

    Used https://etherscan.io/ API to access  data from the blockchain directly.