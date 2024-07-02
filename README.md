# Currency Converter

This project is a simple currency converter application built with React that fetches exchange rates from the ExchangeRate-API. It allows users to convert an amount from one currency to another.

## Features

- Convert an amount from one currency to another
- Display the converted amount based on the latest exchange rate
- Support for multiple currencies

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/aakilshihafv/currency-Converter
    cd currency-Converter
    ```

2. Install dependencies:
    ```sh
    npm install
    ```

3. Start the development server:
    ```sh
    npm start
    ```

## Usage

- Enter the amount you want to convert in the input field.
- Select the currency you are converting from.
- Select the currency you are converting to.
- The converted amount will be displayed based on the latest exchange rate.

## File Structure

- `App.js`: Main application component that handles user input, fetches exchange rate data, and displays the results.
- `App.css`: Styles for the application.

## React Hooks Used

- `useState`: Used to create state variables `amount`, `fromCurrency`, `toCurrency`, `convertedAmount`, and `exchangeRate`.
- `useEffect`: Used to fetch the exchange rate data whenever the `fromCurrency` or `toCurrency` changes, and to calculate the converted amount whenever the `amount` or `exchangeRate` changes.

## API Key

The application uses the ExchangeRate-API to fetch exchange rate data. You may need an API key depending on the service. For demonstration purposes, the URL used in the code does not require an API key. Ensure you update the URL if you are using a different service or need to include an API key.

## Screenshot

![Currency Converter](https://github.com/aakilshihafv/currency-Converter/blob/main/image/currenyConverter%20Design.png)

## Contributing

Feel free to fork this repository, make enhancements, and submit pull requests. Contributions are always welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.

# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
