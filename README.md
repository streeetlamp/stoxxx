# Stocks!

A free, lightweight, blazing-fast static page to get stock quotes using the [IEX API](https://iextrading.com/developer/). Stocks can be grouped into user-defined portfolios. Quotes update every 10 seconds. No API key required. Everything is contained within index.html, there are no external javascripts or stylesheets to load.

See here for a live demo: http://toddwschneider.com/stocks/


## Customize

Edit the `PORTFOLIOS` variable within `index.html`. For example, if you wanted to see the collection of bank stocks and tech stocks from the above screenshot, you could do this:

```js
const PORTFOLIOS = [
  {'name': 'Banks', 'symbols': ['GS', 'MS', 'JPM']},
  {'name': 'Tech', 'symbols': ['AAPL', 'GOOGL', 'MSFT', 'AMZN']}
];
```
