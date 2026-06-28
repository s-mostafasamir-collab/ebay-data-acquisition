# eBay Electronics Dashboard

A data scraping and visualization project that collects electronics data from eBay , and displays it in an interactive dashboard.

---

## What This Project Does

- Scrapes eBay electronics categories using BeautifulSoup
- Fetches Amazon electronics products and prices using SerpAPI
- Scrapes product reviews using Selenium
- Visualizes data with bar charts, heatmaps, network graphs, and 3D point clouds
- Displays everything in an interactive Tkinter dashboard
- Includes a product recommendation system based on co-occurrence
- Detects product communities using NetworkX

---

## Technologies Used

- Python
- BeautifulSoup4 — web scraping
- Selenium — browser automation
- SerpAPI — fetching Amazon products
- Pandas — data processing
- Matplotlib & Seaborn — data visualization
- NetworkX — network graphs and community detection
- Tkinter — desktop GUI dashboard
- NumPy — numerical calculations

---

## How To Run

**Step 1 — Clone the repository**
```
git clone https://github.com/s-mostafasamir-collab/ebay-data-acquisition.git
```
**Step 2 — Install libraries**
```
pip install -r requirements.txt
```
**Step 3 — Set up your API key**
```
cp .env.example .env
Then open `.env` and replace `your_serpapi_key_here` with your real SerpAPI key.
```
**Step 4 — Run the project**
```
python main.py
```
