# cryptocurrency-ticks-data
550 days of trade ticks on BTC/ETH/LTC/NEO to USDT

The data is stored inside a regular zip file.
The data consists of the following columns:
1. Id - id provided by the exchange
2. time - epoch time, UTC.
3. Price - The price in the rhs symbol (e.g. BTCUSDT means price is in USDT)
4. Quantity - Quantity of the lhs symbol (e.g. BTCUSDT means quantity in BTC)
5. IsBuyerMaker - was the trade completed by the buyer (true) or by the seller (false). 
    when it is true, it means that the seller has placed a ask for his holdings and a buyer came along later on and completed the trade.
    when it is false, it means that the buyer has placed a bid for his more curreny and a seller came along later on and completed the trade.
6. BuyerOrderId - Order id of the buyer
7. SellerOrderId - Order id of the seller
8. Was the Maker (buyermaker or sellermaker) accomplish the trade by a market order (I might be wrong tho.)
