# Currency Converter

A browser-based currency converter built with HTML, CSS, and vanilla JavaScript. It retrieves exchange-rate data from the currency-api dataset and displays country flags for selected currencies.

## Features
- Select source and target currencies
- Currency dropdowns populated from a currency-to-country mapping
- Country flag updates when a currency is changed
- Calculates the converted amount using fetched exchange-rate data
- Defaults to USD → INR

## Technologies
- HTML5
- CSS3
- JavaScript
- Fetch API

## Run locally
1. Download or clone this repository.
2. Open `index.html` in a modern browser with an internet connection.
3. Enter an amount, choose currencies, and select **Get Exchange Rate**.

## Project files
- `index.html` — page structure
- `style.css` — styling
- `app.js` — dropdown, flag, and conversion logic
- `code.js` — currency-to-country code mapping

## Data and external services
- Exchange-rate data: `https://cdn.jsdelivr.net/gh/fawazahmed0/currency-api@1/latest/currencies`
- Flag images: `https://flagsapi.com/`

## Notes
An internet connection is required for exchange-rate data and flag images. Rates are sourced from an external dataset and may not represent a live bank or money-transfer quote.
