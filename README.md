# apartmentrankers

### How to Use this Application
* Download this repository as a ZIP
* Open and run Jupyter Notebook to open up _dash app.ipynb_
* Run all cells and open a local version of Apartment Ranker

### Packages Used in Development
* numpy
* math
* pandas
* matplotlib
* sklearn _cosine similarity matrix_
* plotly
* chart_studio
* dash _core components, html components, bootstrap components, dependencies_
* geopandas
* tqdm
* BeautifulSoup
* re

### File directory

* **scraper.ipynb**: scrapes pertinent information from html_files and returns a .csv for manipulation.
* **data cleaning.ipynb**: removes extraneous columns from raw_csvs (not included)
* **feature_counts.ipynb**: creates the full housing data set by counting number of features within 0.25mi
* **recommendation.ipynb**: implements a content-based recommender system
* **dash app.ipynb**: all-in-one application launcher for local uses
* **about.html**: "About me" HTML file, referenced as a tab in =dash app.ipynb=
* **Inventory.html**: "Inventory" HTML file, referenced as a tab in =dash app.ipynb=
* **ApartmentRanker_StyleSheet.css**: CSS stylesheet

### Other important links

* [Intake Survey  - DEPRECATED](https://forms.gle/TmWuWb6TuArVTLDj7)
* [Google Slides - contact for permission if unable to access](https://docs.google.com/presentation/d/1vpxccPpUaReHke6-mVpZjPjLkYvdAIEnlHFjYCKY5mg/edit#slide=id.g773400c8be_2_132)
* [Live ApartmentRanker Demo](http://apartmentranker.herokuapp.com/)
* [Link to reset global dislikes storage (will be fixed in later release\)](http://apartmentranker.herokuapp.com/reset/)


