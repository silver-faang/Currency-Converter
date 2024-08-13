Based on the provided `package.json`, here's the updated `README.md` with the correct tech stack:

---

# Currency Exchange App

## Description

This project is a currency conversion application designed to help users calculate the value of an amount in another currency.

## Features

- **Currency Conversion**: Calculate the value of an amount in another currency.
- **API Integration**: 
  - [Currencies List](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies.json): Retrieve a list of currency codes.
  - [Currency Exchange Data](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/btg.min.json): Retrieve exchange data by replacing `btg` with the appropriate currency code from the list.
- **Routing**: Implemented using `react-router-dom` with three routes:
  1. **Home Page**: Current app functionality.
  2. **Conversion History**: Displays the history of user's currency searches.
  3. **About**: Provides a short description of the application.
- **History Block**:
  - **Home Page**: Shows the last 10 conversion results.
  - **History Page**: Displays all conversion history.
- **Data Storage**: Utilizes React Context for storing history data.

## Tech Stack

- React
- React Router DOM
- Material-UI
- Axios
- JavaScript
- HTML
- CSS

## Setup and Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/silver-faang/Portfolio.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Portfolio
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

## Usage

1. **Currency Conversion**: Enter the amount and select the currencies to convert.
2. **View History**: Navigate to the history page to view past conversions.
3. **About**: Learn more about the application on the about page.

## API References

- [Currencies List](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies.json)
- [Currency Exchange Data(USD)](https://cdn.jsdelivr.net/npm/@fawazahmed0/currency-api@latest/v1/currencies/usd.min.json)

## License

This project is licensed under the MIT License.

---

Does this look good to you? Let me know if there's anything else you'd like to adjust!
