# SteamTagEncoderRecommender
A machine learning system that recommends Steam genre tags and categories for similar games using encoder models trained on scraped product page data.

**Short Description:**
A machine learning system that recommends Steam genre tags and categories for similar games using encoder models trained on scraped product page data.

**Detailed Implmentation:**
A deep learning–based approach was selected due to its effectiveness in modeling high-dimensional and sparse datasets. The Steam platform provides a large-scale dataset of over 100,000 games, each associated with diverse genres, tags, and metadata. This rich feature space makes it well-suited for neural network architectures, which can learn complex, non-linear relationships between attributes.

To leverage this, an encoder-based model is used to transform game metadata into dense representations, enabling the system to capture similarities and patterns across different titles. By learning these latent feature embeddings, the model can better differentiate products and generate more accurate recommendations. The following Steam dataset can be found on Kaggle through the provided link. 

**Programming Languages:**
Python

**APIs:**
PANDAS, Numpy, Seaborn, Scikit-learn, and TensorFlow.

**Kaggle Dataset Link:**
https://www.kaggle.com/datasets/artermiloff/steam-games-dataset?resource=download

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]
(https://colab.research.google.com/github/funkeymonkey10/SteamTagEncoderRecommender/blob/main/FinalProject.ipynb)

<img width="559" height="329" alt="Screenshot 2026-03-23 173148" src="https://github.com/user-attachments/assets/93833c14-67b8-4833-afca-3de4d8ced36c" />

<img width="455" height="350" alt="image" src="https://github.com/user-attachments/assets/4c177a77-97d9-469b-b8f6-18873aeea4cf" />
