# Amazon Product Finder

Searches Amazon by keyword and finds potential products to sell based on certain criteria such as number of vendors, buybox price, and whether it's sold by Amazon.

## Getting Started

Clone the repository, run `npm i`, and then `npm start` in a terminal/bash/command prompt.

It will output an array of product objects with items like price, brand name, and total buybox vendors.

You can adjust the criteria easily by adjusting the variables found at the top of src/index.ts.

There are script options to run this headless or on an ubuntu webserver.

To run on ubuntu:

```
npm run start:ubuntu
```

To run headless:
```
npm run start:headless
```

[Full Guide](https://javascriptwebscrapingguy.com/blog/jordan-scrapes-amazon-looking-for-products-to-sell/)

### Prerequisites

Tested on Node v8.11.2 and NPM v5.6.0.

### Installing

After installing [NodeJS](https://nodejs.org/en/) you should be able to just run the following in the terminal.

```
npm i
```

## Built With

* [Puppeteer](https://github.com/GoogleChrome/puppeteer) - Scraping library
* [NodeJS](https://nodejs.org/en/) - NodeJS

## Authors

* **Jordan Hansen** - *Initial work* - [Jordan Hansen](https://github.com/aarmora)


## License

This project is licensed under the ISC License
