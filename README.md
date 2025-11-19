# Global Coffee Quality Analysis

## Project Summary  
This project explores global coffee quality using open data from the Coffee Quality Institute (CQI). It applies clustering, regression modeling, and geospatial mapping to uncover flavor trends, roast-level distributions, and economic context across producing countries. The final analysis is presented in a stakeholder-friendly Tableau storyboard.

---

## Data Access  
Raw data files are not included in this repository. You can download them from the following sources:

- **Coffee Quality Database**  
  [https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi](https://www.kaggle.com/datasets/volpatto/coffee-quality-database-from-cqi)

- **Top Rated Coffee**  
  [https://www.kaggle.com/datasets/asimmahmudov/top-rated-coffee](https://www.kaggle.com/datasets/asimmahmudov/top-rated-coffee)

- **Time Series Data (Coffee Production by Region)**  
  [https://ourworldindata.org/grapher/coffee-production-by-region](https://ourworldindata.org/grapher/coffee-production-by-region)

Once downloaded, place the files in a local `data/` folder to run the scripts as intended.

---

## Tableau Storyboard  
Explore the final insights in the published Tableau storyboard:  
https://public.tableau.com/app/profile/chase.bjerke/viz/GlobalCoffeeQualityAnalysis/GlobalCoffeeQuality?publish=yes
> _Note: This storyboard highlights key results and visuals. Intermediate steps and exploratory analysis are documented in the scripts and portfolio case study._

---

## Key Questions Explored  
- Which countries consistently produce high-scoring coffees?  
- Which roast levels consistently receive higher scores?  
- How does coffee quality vary by roast level across different countries?  
- Which roast levels deliver the most consistently high cupper scores?  
- Which countries consistently lead or lag in sensory quality scores?

---

## Tools & Technologies  
- Python (Pandas, NumPy, Scikit-learn, Folium)  
- Tableau (Storypoint dashboard)  
- GitHub (version control and portfolio hosting)

---

## Code Overview  
All code was written in Python and executed using Jupyter notebooks. The following libraries were used throughout the analysis:

- pandas: Data manipulation and cleaning  
- numpy: Numerical operations and array handling  
- os: File and directory handling  
- matplotlib.pyplot: Static and interactive visualizations  
- matplotlib.ticker.FuncFormatter: Custom axis formatting  
- seaborn: Statistical data visualization  
- scipy: Advanced mathematical functions and statistical tools  
- scikit-learn (sklearn): Clustering (KMeans), regression modeling, and data preprocessing  
- folium: Interactive geospatial mapping  
- json: Handling GeoJSON files for map overlays  
- warnings: Suppressing non-critical warnings during execution  
- pathlib: Cross-platform file path handling (used in some scripts for clarity and portability)

Each script is annotated for clarity and auditability, with comments explaining transformation logic, modeling decisions, and visualization choices.

---

## Disclaimer  
This project was developed as part of the CareerFoundry Data Analytics Program. It is intended for educational and portfolio purposes only. All data sources are publicly available and cited accordingly.
