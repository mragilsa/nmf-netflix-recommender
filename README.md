# NMF Netflix Recommender System

This repository contains a Python notebook implementing a **Netflix movie recommendation system** using **Non-negative Matrix Factorization (NMF)**.

## **Setup & Dataset**

1. **Clone repository:**
```bash
git clone https://github.com/mragilsa/nmf-netflix-recommender.git
```
```
cd nmf-netflix-recommender
```

2. **Download the dataset from Kaggle:**  
   - [Kaggle link](https://www.kaggle.com/datasets/rishitjavia/netflix-movie-rating-dataset?select=Netflix_Dataset_Rating.csv)
   - Save the CSV file as `Netflix_Dataset_Rating.csv` in the same folder as the notebook (`nmf_recommender.ipynb`).

## **Run the Notebook**

1. Install required packages:
```bash
pip install pandas numpy scikit-learn matplotlib
```

2. Open the notebook:
```bash
jupyter notebook nmf_recommender.ipynb
```

3. Make sure the notebook reads the CSV from the `data/` folder:
```python
df = pd.read_csv("data/netflix_ratings.csv")
```

4. Run all cells to train NMF and generate recommendations.
