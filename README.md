# Data-capstone-project
Country Data Capstone Project

A beginner-friendly pandas data analysis project exploring country-level demographic, geographic, economic, and political data. The analysis is presented in the Jupyter notebook [`Data capstone project.ipynb`](Data%20capstone%20project.ipynb).

## Dataset

The notebook uses `Countries.csv`, a country dataset with 194 rows and 64 columns. Fields include country and region, continent, population, urban and rural population, women’s parliamentary representation, press score, democracy score and regime type, median age, and political leadership.

In this folder, the CSV is located in `Dataset/Countries.csv`. The notebook currently loads it with:

```python
df = pd.read_csv('Countries.csv')
```

Either run the notebook with its working directory set to the `Dataset` folder, or update the path to `pd.read_csv('Dataset/Countries.csv')` when running it from this project folder.

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab
- pandas
- NumPy

Install the Python packages if needed:

```bash
pip install pandas numpy jupyter
```

## Run the notebook

1. Make sure the CSV path in the notebook matches your working directory (see above).
2. Start Jupyter from this folder:

   ```bash
   jupyter notebook
   ```

3. Open `Data capstone project.ipynb` and run the cells in order.

## Analysis covered

The notebook loads and inspects the dataset, then uses pandas filtering, sorting, counts, and aggregations to answer questions such as:

- Which five countries have the highest democracy scores?
- How many distinct regions are represented, and which countries are in Eastern Europe?
- Who is the political leader of the second most populous country?
- How many countries have no listed political leader?
- How many countries have “Republic” in their full name?
- Which African country has the largest population?

The results depend on the values and coverage in the provided dataset. The notebook’s democracy scores are dataset values and are not independently recalculated here.
