# Bots on Twitter: An Exploratory Analysis Approach on The Content they Share

## Project Overview
This repository contains the code for one of my second semester Master's term papers for the course "Web & Society: A Computational Social Science Perspective". For the term paper, Trinidad Bosch Achondo and I investigated the role of bots on social media in light of widespread concerns about a "malicious social bot pandemic". We focused on analysing the topics that bots discuss, the sentiments that they convey, and whether we can find evidence of malicious intent.

## Objectives
- Identify the main topics discussed by social media bots and valid users.
- Analyse the sentiment (positive, negative, neutral) associated with these topics.
- Evaluate whether the bots' interactions are indicative of malicious intent.

## Key findings
- Bots primarily discuss current and trending topics, similar to valid users.
- Bots do not universally associate topics with a sentiment, the way they associate a topic depends primarily on the areas they are exploring. For example, the topic 'stock markets' has a fairly neutral sentiment.
- No overarching malicious intent was found, although this can vary from topic to topic.

## Technologies and Tools
- Web Scraping
- Data Preprocessing
- Natural Language Processing
- LLM BERT Embeddings
- Dimensionality Reducation UMAP
- Cluster Detection HDBSCAN and k-Means 
- Topic Modelling
- Sentiment Analysis
- Data Visualisation

## Repository Contents
- `script`: Jupyter notebook that contains the the whole project's code including the data collection, preprocessing, and analysis.
- `requirements`: List of Python packages required to run the project.
- `paper`: PDF of final term paper.

**Note:** We cannot provide the raw data used in this project as it belongs to the ‘TwitBot-20’ dataset (Feng et al., 2020) of which we are not owners. Processed datasets are also not included due to these restrictions.
-  Original Dataset: Feng, S., Wan, H., Wang, N., Li, J., & Luo, M. (2021). TwiBot-20: A comprehensive Twitter bot detection benchmark. In G. Demartini, G. Zuccon, J. S. Culpepper, Z. Huang, & H. Tong (Eds.), Proceedings of the 30th ACM International Conference on Information & Knowledge Management (pp. 4485–4494). ACM. https://doi.org/10.1145/3459637.3482019
-  Related publication: Feng, S., Tan, Z., Wan, H., Wang, N., Chen, Z., Zhang, B., ... & Luo, M. (2022). TwiBot-22: Towards Graph-Based Twitter Bot Detection. arXiv preprint arXiv:2206.04564.

## Installation
To run the code in this repository, you'll need to have Python installed. Clone this repository and install the required packages using:

git clone [repository-link]
cd [repository-name]
pip install -r requirements.txt

## Contact
For any questions or further information, please contact:

Gina-Maria Angelina Unger - gina-unger@gmx.de
Trinidad Bosch Achondo - tbosch.achondo@gmail.com
