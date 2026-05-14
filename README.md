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
### 🎤 [Grammy Rap Albums Discord Bot](https://github.com/fghlewis/Rap-Music-Discord-Bot)
**Question:** What makes a Grammy-winning rap album distinctive — lyrically and sonically — and can those differences be made interactive and explorable?
- Scrapes every Grammy-winning rap album (1996–2024) from Wikipedia and collects full track lyrics via the Genius API, storing everything in a structured JSON dataset
- Performs sentiment analysis at the track and line level using NLTK's VADER, visualizing emotional arcs per song and per album directly in Discord
- Analyzes word frequency across albums using spaCy tokenization, lemmatization, and stop word removal, returning a ranked bar chart of the top 30 words
- Counts syllable complexity per album using a three-layer fallback system: CMU Pronouncing Dictionary → Pyphen hyphenation → vowel counting
- Detects end-of-line rhyme schemes track-by-track using the `pronouncing` library, mapping patterns to letter notation (AABB, ABAB, etc.)
- Pulls per-track audio features (danceability, energy, valence, tempo, loudness, etc.) from the ReccoBeats API and visualizes them as point plots in Discord
- Includes a separate Altair notebook with interactive dropdown charts for exploring sentiment across all albums and tracks statically

#### 🧰 Tools & Skills Used
- **Languages:** Python
- **APIs:** Genius API, Spotify API, ReccoBeats API
- **Lyrical Analysis:** NLTK (VADER), spaCy, pronouncing, pyphen, lyricsgenius
- **Data & Visualization:** pandas, NumPy, Seaborn, Matplotlib, Altair
- **Bot Framework:** discord.py (async), discord.ext.commands
- **Supporting Libraries:** os, asyncio, json, collections, python-dotenv

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


