# 📊 George Lewis – Data Analysis Portfolio

Hi! Welcome to my data analysis portfolio. I'm a Business Information Systems major (minor in Information Science) at the University of Colorado Boulder with a goal of someday becoming a data Engineer! This portfolio showcases some various personal projects I've worked on over the past two years.

---
## 🔍 Projects

### 🎵 [Movie Soundtrack Analysis](https://github.com/fghlewis/Movie-Soundtrack-Analysis)
**Question:** How do movies with rap soundtracks perform from those without?  
- Uses movie data to compare genres, gross earnings, IMDb and MPAA ratings, and release trends  
- Includes various data collection/wrangling methods, cleaning, and visual exploration

#### 🧰 Tools & Skills Used
- **Languages:** Python (Pandas, NumPy, re, requests, BeautifulSoup, Matplotlib, Seaborn)
- **IDE's:** Jupyter Notebooks, VS Code
- **Other:** Data wrangling, EDA, regression, groupby analysis, visualization

---

### 🎵 [Discogs x Spotify Music Analysis Discord Bot](https://github.com/fghlewis/INFO3510-Project2)
**Question:** Does Discogs community data accurately reflect what audiences are actually listening to, and can audio properties explain why?
- Queries the Discogs API for an artist's top 3 albums ranked by community "Haves," "Wants," and average rating, and sends results + bar charts directly to Discord
- Queries the Spotify API for the same artist's top 3 albums by Spotify's popularity score (0–100) for cross-platform comparison
- Pulls per-track audio features (danceability, energy, liveness, speechiness, valence) from the ReccoBeats API, averages them across an album, and visualizes results in Discord
- Scrapes all physical and digital variants of a given album from Discogs (vinyl, LP, CD, etc.) and stores release metadata in a local SQLite database via `pandas.to_sql()`
- Outputs all DataFrames as clean grid-formatted tables in Discord using `pandas.to_markdown()`

#### 🧰 Tools & Skills Used
- **Languages:** Python, SQL
- **APIs:** Discogs API, Spotify API, ReccoBeats API
- **Data & Visualization:** pandas, NumPy, Seaborn, Matplotlib
- **Bot Framework:** discord.py (async), discord.ext.commands
- **Data Storage:** sqlite3, pandas `.to_sql()`
- **Supporting Libraries:** os, asyncio, requests, python-dotenv

---

### 📂 [Multi Account Web Scraper](https://github.com/fghlewis/Multi-Account-Web-Scraper)
**Question:** How can we build a web scraper that logs into a website using different accounts and saves both the login info and the scraped data into a database?
- Logs into a target website using rotating credentials pulled from a local SQL database
- Scrapes protected content using Playwright with async functionality
- Securely stores login details and scraped data in separate, relational tables
- Uses encryption (Fernet) to safely store passwords
- Automates data collection using Python’s scheduling and timing libraries
- Designed for modularity, scalability, and stealth scraping patterns

#### 🧰 Tools & Skills Used
- **Languages:** Python, SQL
- **Data Storage:** pandas, sqlite3
- **Encyrption and Security:**: Cryptography Fernet
- **Web Scraping**: BeautifulSoup (lxml parser), Playwright (async version)
- **Supporting Libaries**: os, datetime, time, asyncio, random

---

## 🖥️ Information Retrieval System Designs (with Queries)

### Structured Retrieval (Relational Database)

---

### 📄 Document-Oriented Retrieval (MongoDB)

---

### 🔎 Search Engine Retrieval (Elasticsearch)

---

### ⩬ Semantic Retrieval (Retrieval Augmented Generation)

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](https://www.linkedin.com/in/frederikgeorgelewis/) 

Or reach out via email: contact.georgelewis@gmail.com


