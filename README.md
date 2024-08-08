# Block and Transaction Statistic

## License

The code in this branch is licensed under GPLv3 (see LICENSE file)
Feel free to modify or reuse the code here.
## Installation

```
git clone https://github.com/brilliantdev5/statistic-transaction
npm install
bower install
npm start
```

Make sure to install geth as well for the ETH explorer to be able to function. Then run:
```
geth --rpc --rpcaddr localhost --rpcport 8545 --rpcapi "web3,eth" --rpccorsdomain "http://localhost:8000"
```

Then visit http://localhost:8000 in your browser of choice after you npm start the explorer

## Updates since original etherpaty/explorer base:

- Regular Expressions completed for Addresses, Block #s, and Transacions IDs (aka Search works great)
- The theme is based off Bootstrap V3 for responsive design.
- You can easily change from a cosmo or light theme utilizing https://bootswatch.com
- There is a basic API implemented now as well as well as a Ethereum Blockchain Information page
- Realtime ETH/USD Price Ticker
- Realtime Ethereum Hashrate
- Address Pages are integrated with Shapeshift to easily send a payment to an address.
- Responsive design
- Fontawesome Icons
- Block Time Averages
- Gas Prices/Limits
- Total/Current Difficulty
- Realtime latest blocks and recent transactions
- Other random blockchain info stats were added

_If you want to disable auto refresh/auto new block show, just comment line no 13-22 at: [app/scripts/controllers/mainController.js]
