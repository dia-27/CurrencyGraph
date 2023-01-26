
## Using the CoinGecko Api to obtain currency and create a currency graph

This notebook explains how to use the CoinGecko API to obtain the price of a specific digital currency in any other digital currency. after this it plots a candle graph in relation to the currency and dollars.





## Documentation
Documentation for the CoinGecko Api is provided here
[Documentation](https://www.coingecko.com/en/api/documentationn).

Documentation for mplfinance to create a candlestick graph is given [here](https://pypi.org/project/mplfinance/)


## Libraries used
1. Pandas
2. pycoingecko
3. datetime
4. matplotlib
5. mplfinance
## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Id and vs_currencies |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of currency to fetch and Id in what it needs to be fetched |

#### get_price(ids, vs_currency) takes
 a digital currency whose value must be determined and in what currency it must be determined.



