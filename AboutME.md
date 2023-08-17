# Video Games Sales Analysis 📊

## About Dataset 📂

This dataset contains information on video games that have achieved sales of over 100,000 copies. The data originates from a scrape of [vgchartz.com](http://vgchartz.com).

### Dataset Fields:

- **Rank**: Ranking based on overall sales.
- **Name**: Name of the game.
- **Platform**: The release platform for the game (e.g., PC, PS4).
- **Year**: The year the game was released.
- **Genre**: Game's genre.
- **Publisher**: Game's publisher.
- **NA_Sales**: Sales figures from North America (in millions).
- **EU_Sales**: Sales figures from Europe (in millions).
- **JP_Sales**: Sales figures from Japan (in millions).
- **Other_Sales**: Sales figures from other parts of the world (in millions).
- **Global_Sales**: Cumulative global sales.

The data was scraped using a script that leverages BeautifulSoup in Python. You can find the scraping script [here](https://github.com/GregorUT/vgchartzScrape). From the total of 16,598 records, 2 were excluded due to missing data.

### Direct Dataset Links:

- [Kaggle: Video Game Sales](https://www.kaggle.com/datasets/gregorut/videogamesales)
- [Kaggle: Video Games Developers](https://www.kaggle.com/datasets/andreshg/videogamescompaniesregions?select=video-games-developers.csv)

## Table of Content 📋

1. **Loading Data** 📚
2. **Pandas Profiling** 🔎
3. **Released Games by Year** 📝
4. **Sales Analysis** 💵
5. **Sales Distribution** 📈
6. **Distribution of Sales by Genre** 🙅
7. **Sales Distribution by ESRB Rating** 🔞
8. **Publisher Analysis** 📸
