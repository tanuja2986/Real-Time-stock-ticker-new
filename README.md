📈 Real-Time Stock Ticker

A real-time stock price tracker web application that displays the latest stock market data and visualizes price trends using the Alpha Vantage API.
It helps users monitor live stock prices and analyze market movements in an interactive and user-friendly interface.

🧠 Project Objective

The main objective of this project is to develop a real-time web-based stock ticker that provides users with instant access to updated stock data.
The system is designed to:

* Fetch real-time market data using an external API.
* Display the latest stock price and a visual representation of price movement.
* Offer a simple and interactive user interface.
* Demonstrate practical API integration and data visualization techniques using web technologies.

🌟 Key Features

* Live Stock Updates– Fetches the most recent stock price using the Alpha Vantage API.
* Interactive Charts– Displays recent stock performance trends in an interactive chart.
* User-Friendly Interface– Clean, responsive, and intuitive interface.
* API Integration– Connects to Alpha Vantage for live data retrieval.
* Error Handling– Handles invalid inputs and API rate limits gracefully.
* Lightweight Frontend– Fully client-side, built using HTML, CSS, and JavaScript.

⚙️ How It Works

1. The user enters a stock symbol (e.g., MSFT, AAPL, TSLA) in the input field.
2. When the “Get Stock Price” button is clicked, the app fetches data from the Alpha Vantage API.
3. The latest stock price and a five-day trend are displayed on the screen.
4. A dynamic chart visualizes the price changes.
5. If an invalid symbol is entered or the API call fails, an error message is shown.

 🏗️ Tech Stack

* Frontend:HTML5, CSS3, JavaScript
* API:Alpha Vantage (Stock Market Data API)
* Charting Library:Chart.js
* Hosting: GitHub Pages
* Version Control:Git + GitHub

 📂 Project Structure

The project includes the following main files and folders:

* `index.html` – Main webpage file
* `style.css` – Styling for the user interface
* `script.js` – Core logic for API calls and chart rendering
* `assets/` – Folder containing screenshots and demo images
* `README.md` – Project documentation
* `report/` – Contains the final project report

🚀 Live Demo

You can view the live version of the project at the link below:

👉 [Live Demo – Real-Time Stock Ticker](https://tanuja2986.github.io/real-time-stock-ticker/)

*(If the link doesn’t load, ensure the repository is deployed using GitHub Pages under “Settings → Pages”.)*

 🧰 API Details

* API Provider:Alpha Vantage
* Endpoint Used:TIME_SERIES_DAILY
* Purpose:Fetches daily stock market prices for a specific symbol.
* Data Returned:Opening, closing, high, and low prices for the selected stock.

This project uses the free Alpha Vantage API key for testing and demonstration purposes.

📸 Demo Screenshots

 Homepage

![Demo Screenshot](assets/demo.png)

🚧 Challenges Faced

| Challenge                                             | Solution                                                      |
| ----------------------------------------------------- | ------------------------------------------------------------- |
| API rate limit (5 calls per minute for free accounts) | Added user instructions to obtain a free API key.             |
| Chart rendering issues                                | Implemented Chart.js with real-time data updates.             |
| Invalid stock symbols                                 | Added input validation and descriptive error messages.        |
| GitHub Pages deployment                               | Ensured correct repository structure with index.html in root. |



🏁 Conclusion

The Real-Time Stock Ticker project successfully demonstrates the integration of live financial data and interactive data visualization on the web.
It serves as a practical example of API handling, asynchronous JavaScript usage, and modern web application design.
This project lays a solid foundation for building advanced financial analytics and investment tracking platforms.

