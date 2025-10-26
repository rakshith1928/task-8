📌 Project Overview

This project applies K-Means Clustering to the Mall Customers dataset to segment customers based on their purchasing behavior.
By identifying distinct customer groups, businesses can better target marketing strategies, personalize offers, and improve customer engagement.

⚙️ Steps Performed

Load and Explore Dataset

Imported the dataset using Pandas.

Performed basic visualization of features.

Preprocessing

Selected key features: Annual Income (k$) and Spending Score (1–100).

Standardized features using StandardScaler.

K-Means Clustering

Applied K-Means algorithm to group customers.

Assigned cluster labels to each customer.

Elbow Method

Determined the optimal number of clusters (k) by plotting inertia values.

Chose the “elbow point” for best clustering.

Cluster Visualization

Visualized clusters in 2D space with color-coded labels.

Marked cluster centroids for clarity.

Evaluation

Measured clustering performance using Silhouette Score.

Higher silhouette value indicates well-defined clusters.

(Optional) PCA

Reduced high-dimensional data into 2D for visualization.

Plotted PCA projections with clusters.

📊 Results

The Elbow Method suggested k ≈ 5 clusters.

Clusters show distinct customer segments such as:

High Income – High Spending

Low Income – Low Spending

High Income – Low Spending

Average Income – Balanced Spending

Achieved a Silhouette Score that indicates good separation between clusters.
