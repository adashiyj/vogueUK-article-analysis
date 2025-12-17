# README

### Setup requirements
- Python 3.9+ (I'm using 3.12.7)
- Google Colab or a local machine with GPU support
- `!pip install pandas numpy torch transformers datasets scikit-learn bertopic spacy emoji accelerate`
- A valid YouTube Data API v3 key

### Code
The following Jupyter notebooks can be run locally
- `data_collection.ipynb`
- `data_cleaning.ipynb`
The following Jupyter notebook is recommended to run on GPU
- `data_analysis.ipynb` (for stepwise SML, UML, and descriptive analysis - as sampling didn't set seed, the output can vary each time, so certain steps must be run with provided CSV or XLSX files)




