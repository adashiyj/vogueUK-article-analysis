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

### Dataset
- `youtube_comments.csv` is the output of `data_collection.ipynb`
- `youtube_comments_clean.csv` is the output of `data_cleaning.ipynb`
- `relevance_label_sample.xlsx` is the sample for step 1 manual coding (and results are also saved)
- `youtube_comments_relevance_labled.csv` is the complete dataset with manually coded results being integrated
- `youtube_comments_relevance_trained.csv` is the complete dataset after step 1 SML
- `agreement_label.xlsx` is the remaining sample for step 2 manual coding (and results are also saved)
- `youtube_comments_agree_labled.csv` is the complete dataset with manually coded results being integrated
- `youtube_comments_agree_trained.csv` is the final complete dataset 

### Media output
- Figures
- BERTopic documents




