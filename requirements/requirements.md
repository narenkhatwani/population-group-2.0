**Requirements**

The following Python libraries are required to run the scripts in this repository:

- `requests` – for querying the PubMed API
- `csv` – for reading and writing input/output data files
- `re` – for keyword pattern extraction using regular expressions
- `datetime` and `timedelta` – for filtering publications by date
- `tqdm` – for displaying progress bars during concept processing
- `collections.Counter` – for efficient keyword frequency counting
- `matplotlib.pyplot` – for rendering visualizations
- `wordcloud` – for generating word cloud visualizations
- `pandas` – for loading and manipulating tabular data

You can install all dependencies using:

```bash
pip install -r requirements.txt