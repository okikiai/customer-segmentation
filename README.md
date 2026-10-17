# Customer Segmentation

A customer segmentation project using Python and K-Means clustering to identify groups of customers with similar purchasing characteristics.

## Project Overview

Customer segmentation is the process of dividing customers into meaningful groups based on shared characteristics.

In this project, I explored customer data and applied **K-Means clustering** to identify distinct customer segments. The analysis focuses on understanding the structure of the data and determining a suitable number of clusters.

## Objectives

- Explore and understand the customer dataset
- Analyze relationships between customer characteristics
- Apply K-Means clustering
- Use Within-Cluster Sum of Squares (WCSS) to evaluate different numbers of clusters
- Select an appropriate number of clusters
- Visualize the resulting customer segments
- Visualize the cluster centroids

## Dataset

The project uses the **Mall Customers dataset**, which contains information about customers including:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

The dataset is included in this repository as `Mall_Customers.csv`.

## Methodology

The project follows these main steps:

1. **Data Loading**
   - Loaded the customer dataset using Pandas.

2. **Exploratory Data Analysis**
   - Examined the structure and characteristics of the dataset.
   - Explored relevant customer features for segmentation.

3. **K-Means Clustering**
   - Applied the K-Means clustering algorithm to group customers based on their characteristics.

4. **Choosing the Number of Clusters**
   - Calculated WCSS for different numbers of clusters.
   - Used the resulting values to identify an appropriate cluster count.

5. **Customer Segmentation**
   - Built the K-Means model using the selected number of clusters.
   - Assigned each customer to a cluster.

6. **Visualization**
   - Visualized the resulting customer groups.
   - Plotted the cluster centroids to make the segmentation easier to interpret.

## Result

The analysis identified **3 customer clusters** as the selected segmentation structure for this project.

The resulting clusters provide a simple way to distinguish groups of customers based on similarities in the selected features.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
customer-segmentation/
│
├── .gitignore
├── Mall_Customers.csv
├── analysis.ipynb
└── README.md
```

## What I Learned

This project helped me practice:

- Exploratory data analysis
- Unsupervised machine learning
- K-Means clustering
- WCSS and cluster selection
- Data visualization
- Working with Jupyter Notebooks
- Using Git and GitHub to document and share machine learning projects

## Future Improvements

Possible next steps include:

- Comparing K-Means with hierarchical clustering
- Testing different feature combinations
- Scaling features before clustering
- Evaluating cluster quality using additional metrics
- Developing more detailed profiles for each customer segment
- Exploring how the segments could support marketing or business decisions

## Author

**OKIKI**

Applied Machine Learning | Supply Chain & Economic Systems