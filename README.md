<div align="center">
<img width="100px" alt="StockPrice" src="public/icons/android-chrome-512x512.png">
<br>
<h2>Stock Price Checker 🚀</h2>
</div>
<hr>

## Objective

- #### Build a full stack JavaScript app that is functionally similar to this: https://stock-price-checker.freecodecamp.rocks/

# Project Stock Price Checker

- Add `.env` file to the project

- ``SET NODE_ENV`` to `test` 

- Set DB to your mongo connection string

- Complete the project in `routes/api.js` or by creating a handler/controller

- You will add any security features to `server.js`

- You will create all of the functional tests in `tests/2_functional-tests.js`

## Technologies

- Node
- Express
- Helmet
- Mocha-Chai
- MongoDB
- javascript
- Html
- CSS

## Installation:

- clone this repository
```
$ git clone https://github.com/RiteshPuvvada/Stock-Checker.git

$ cd Stock-Checker

$ npm install

$ npm start or npm run dev 
```

## Usage:

```
/api/stock-prices?stock=goog
/api/stock-prices?stock=goog&like=true
/api/stock-prices?stock=goog&stock=msft
/api/stock-prices?stock=goog&stock=msft&like=true
```
