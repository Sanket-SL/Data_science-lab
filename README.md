# Data Science Lab

Course work for Data Science III.

## Lab 1 - Data Collection

`Lab-1/Lab_Data_Collection_Simple.ipynb` contains a complete data-collection experiment using APIs and web scraping.

The notebook collects:

- 21 complete days of hourly temperature and relative humidity for MG Road, Whitefield, Jayanagar, Hebbal, and Electronic City
- 30 complete days of hourly PM10, PM2.5, and carbon-monoxide readings for the same locations
- title, price, and star rating from all pages of Books to Scrape

Running the notebook creates:

```text
bengaluru_weather.csv
bengaluru_air_quality.csv
books_data.csv
```

### Setup

```bash
pip install -r requirements.txt
```

Open the notebook from the `Lab-1` folder and run the cells in order.
