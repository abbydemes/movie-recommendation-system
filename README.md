# Movie-recommendation-system
Movie recommendation system using the CiaoDVD dataset

## Author 
Abeenaele Demesyeux

## Dataset 
The CiaoDVD dataset contains user ratings (1-5) for movies. The dataset is highly sparse, meaning most users rated only a few movies.

# Installation 
- Python 3.10
- pandas
- numpy
- scikit-learn

Install with: 
pip install pandas numpy scikit-learn 

## How to Run
1. Open recsys.ipynb in Juypter Notebook or Pycharm
2. Run all cells in order

## Models
- Global Average
- Item-Based CF (k=30, cosine similarity)

## Results 
- Global Average: RMSE 1.07, MAE 0.81
- Item-Based CF: RMSE 1.08, MAE 0.82
- Precision@5: 0.80
- Recall@5: 0.86

The model did not outperform global average due to dataset sparsity but still ranked relevant movies effectively. 
