### Project: Extracting and Visualizing Stock Data

This project focuses on extracting and visualizing stock data for **GameStop (GME)** and **Tesla (TSLA)**, providing insightful analysis of stock prices and their corresponding revenues over time. By utilizing the **yfinance** library, stock prices were gathered for both companies, and revenue data was scraped from two external resources for **GME** and **TSLA** using **requests** and **BeautifulSoup** (BS4). The data was then plotted over time using **Plotly**, with a clear emphasis on visualizing trends starting from 2021 onward.

#### Key Features:
- **Stock Price Extraction**: The **yfinance** library was employed to pull historical stock data, including open, close, high, low, and adjusted close prices.
- **Revenue Data Scraping**: Using **requests** and **BeautifulSoup (BS4)**, I scraped revenue data from publicly available URLs to supplement the stock price information.
- **Data Cleaning & Processing**: The data was cleaned, formatted, and merged using **pandas** and **numpy** for better analysis and visualization.
- **Interactive Visualization**: Leveraging the **Plotly** library, interactive graphs were created to represent stock price movements and revenue over time.

#### Libraries Used:
- **yfinance**: For downloading stock data.
- **pandas**: For data manipulation and cleaning.
- **numpy**: For numerical operations.
- **requests**: For retrieving data from external sources.
- **BeautifulSoup (BS4)**: For web scraping revenue data.
- **plotly**: For creating interactive visualizations.

#### Skill Aspects:
- **Web Scraping**: Extracting dynamic revenue data using **requests** and **BeautifulSoup** to parse and clean HTML content.
- **Data Wrangling**: Utilizing **pandas** to preprocess and merge data from multiple sources, ensuring consistency and readiness for visualization.
- **Data Visualization**: Crafting engaging and informative visualizations with **Plotly** to depict stock prices and revenue trends in an interactive format.
- **Stock Market Analysis**: Applying analytical skills to interpret trends in stock prices and how they correlate with company revenue.

This project demonstrates a practical application of data extraction, cleaning, and visualization, as well as the ability to manipulate large datasets and present insights in a user-friendly, interactive format.
