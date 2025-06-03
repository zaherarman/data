# Data with Python and Jupyter

A curated set of Jupyter notebooks that develop hands-on proficiency in data science using Python. Projects span from foundational data wrangling and visualization to Bayesian modeling, spatial analysis, and natural language processing.

## Project Highlights

### 1. **Airbnb Listings Data Cleaning & Outlier Detection**
- **What I Did:** Fixed data-type issues, computed IQR manually, imputed missing values by condition, categorized variables, and detected outliers using z-scores and box-plot limits.
- **Tech Stack:** `Pandas`, `NumPy`, `Matplotlib`

### 2. **Bayesian Modeling & Topic Discovery (LDA)**
- **What I Did:** Built a generative Bayesian model with switchpoints using PyMC, evaluated posterior samples, and applied LDA for text topic modeling and interpretation.
- **Tech Stack:** `PyMC`, `NumPy`, `Matplotlib`, `Gensim`, `pyLDAvis`

### 3. **Friday Accident Visualization & Android App Feature Analysis**
- **What I Did:** Created bar plots, pairplots, pie charts, correlation matrices, and cross-tabs using Seaborn and Matplotlib. Explored missing data patterns and dummy variable usage.
- **Tech Stack:** `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`

### 4. **Graph Analysis: Game of Thrones Character Networks**
- **What I Did:** Built character co-occurrence graphs from text, visualized network layouts, and applied centrality measures to analyze character importance over time.
- **Tech Stack:** `NetworkX`, `Pandas`, `Matplotlib`

### 5. **Health Network Accessibility & Spatial Fairness (Toronto)**
- **What I Did:** Queried health facilities from OpenStreetMap, computed driving distances using OSMnx, and created interactive Folium maps overlaid with demographic data.
- **Tech Stack:** `GeoPandas`, `Folium`, `OSMnx`, `Shapely`, `Matplotlib`, `Pandas`

### 6. **NLP Text Preprocessing & Topic Mutual Information Analysis**
- **What I Did:** Used NLTK for tokenization, stop word removal, stemming, frequency counting, and mutual information scoring across labeled topics.
- **Tech Stack:** `NLTK`, `Pandas`, `NumPy`, `Matplotlib`

### 7. **Numpy Linear Regression & Pandas Z-Score Analysis**
- **What I Did:** Implemented linear regression from scratch with Numpy, computed RMSE and R², and performed z-score standardization, row-wise aggregation, and group summaries with Pandas.
- **Tech Stack:** `NumPy`, `Pandas`, `Matplotlib`

### 8. **Review Analysis & Sentiment Scoring (TripAdvisor Data)**
- **What I Did:** Explored sentiment using MI/PMI of words and noun phrases. Visualized review distributions and rolling average trends over time.
- **Tech Stack:** `NLTK`, `Pandas`, `NumPy`, `Matplotlib`

### 9. **Spatial & Epidemiological Analysis (U.S. COVID-19 Deaths)**
- **What I Did:** Worked with shapefiles to build choropleths, track time-series trends, and compare states using normalized death metrics.
- **Tech Stack:** `GeoPandas`, `Shapely`, `Pandas`, `Matplotlib`

### 10. **Time-Series Analysis: Stock Prices & Climate Trends**
- **What I Did:** Conducted downsampling, exponential smoothing, return rate calculations, and cross-correlation analysis on stock and climate data.
- **Tech Stack:** `Pandas`, `NumPy`, `Matplotlib`

### 11. **Wikidata Knowledge Graph & Actor Genre Similarity**
- **What I Did:** Queried country data and actor-film-genre relationships using SPARQL. Used cosine similarity to build actor similarity networks.
- **Tech Stack:** `SPARQL`, `Pandas`, `NumPy`, `Seaborn`, `Matplotlib`, `scikit-learn`

## Tools & Libraries Used
- **Data Wrangling:** Pandas, NumPy  
- **Visualization:** Matplotlib, Seaborn, Folium  
- **NLP:** NLTK, Gensim, pyLDAvis  
- **Graphs & Networks:** NetworkX  
- **Spatial Data:** GeoPandas, Shapely, OSMnx  
- **Bayesian Modeling:** PyMC  
- **APIs:** SPARQL via Wikidata

## Course Info
This repository was developed as part of the **University of Toronto's MIE223: Data Science** course.