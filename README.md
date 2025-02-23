# group-recommender-systems-for-movielens-100K-dataset
# Multi-Dimensional Vector Ranking for Group Recommendation Systems

## Overview
This repository contains an implementation of a novel multi-dimensional vector ranking approach for group recommendation systems. The model leverages historical product ratings to enhance recommendation quality. The approach is evaluated using the MovieLens-100k dataset and compared with traditional recommendation methods.

## Dataset
In this experiment, we utilized the MovieLens-100k dataset, which comprises 100,000 ratings from 943 users across 1,682 films. Each user rated movies on a scale from 1 to 5, with a minimum of 20 ratings per user. Additionally, this dataset includes information on titles, release dates, genres, etc. 

To ensure accuracy and objectivity, we divided the data into two parts:
- **80% for training**
- **20% for testing**

This ensures that each user has ratings in both datasets, maintaining consistency in evaluation.

## Methods
We apply three group recommendation methods, including:
1. **Average Strategy**
2. **Weight Based on Average Rating**
3. **Multi-dimensional Vector Ranking Using ReLU**

## Loss Function
To evaluate the effectiveness of the recommendation methods, we employ:
- **ROC (Receiver Operating Characteristic) measure**
- **AUC (Area Under Curve) index**

The ROC measure compares the accuracy of movie recommendations against actual outcomes by considering the **True Positive Rate** and **False Positive Rate**. The AUC value represents the area under the ROC curve, with higher values indicating greater accuracy of the recommendation system.

## Installation
To set up the project, follow these steps:

```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

...

## Usage
Run the Jupyter Notebook to execute the model and evaluate results:

```bash
jupyter notebook group-recommender-systems-for-movielens-dataset.ipynb
```

## Performance Comparison
The implemented method is compared with traditional recommendation techniques based on key metrics:

| Method | Precision | Recall | RMSE |
|--------|-----------|--------|------|
| Multi-Dimensional Vector Ranking | X.XX | X.XX | X.XX |
| Average Strategy | X.XX | X.XX | X.XX |
| Weight Based on Average Rating | X.XX | X.XX | X.XX |

## Contribution
Contributions are welcome! Feel free to submit pull requests or open issues for discussion.

## License
This project is licensed under the MIT License.

## Contact
For any questions, please contact duongchitrung1104@gmail.com .

