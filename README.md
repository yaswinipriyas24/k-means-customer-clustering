<<<<<<< HEAD
# Customer Segmentation using K-Means Clustering

### Overview 📊

This project uses the K-Means clustering algorithm to segment customers based on their Annual Income and Spending Score. The goal is to identify distinct customer groups for targeted marketing strategies. The analysis is performed on the "Mall_Customers.csv" dataset.

### Key Features ✨

* **Data Exploration:** Initial analysis of the dataset to understand its structure.
* **Elbow Method:** Application of the Elbow Method to determine the optimal number of clusters.
* **K-Means Clustering:** Implementation of the K-Means algorithm with 5 clusters.
* **Data Visualization:** Visualization of the resulting clusters and their centroids.

### Prerequisites 🛠️

To run this project, you need the following Python libraries. You can install them using pip:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn
```
## Dataset 📂
The project uses the Mall_Customers.csv dataset, which contains customer information including their Gender, Age, Annual Income (k$), and Spending Score (1-100). The K-Means model is trained on the last two columns: Annual Income and Spending Score.

## Results 📈
The Elbow Method graph suggests that the optimal number of clusters is 5.

The final visualization shows the 5 distinct customer segments identified by the K-Means algorithm. Each cluster is represented by a different color, with the yellow stars marking the cluster centroids.

### How to Run the Code 🚀
Make sure you have all the prerequisites installed.

Download the Mall_Customers.csv file and place it in the same directory as the Python script.

Execute the Python script from your terminal:
``` bash
python clusters.py
```
=======
# k-means-customer-clustering
>>>>>>> de070cc1dac11ce3e098929b3784d01dd880b685
