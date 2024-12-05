# Wholesale-Customer-Clustering-
WholesaleInsights

This project demonstrates how to cluster wholesale customer data using the KMeans algorithm. The goal is to identify customer segments for targeted marketing strategies. 

## **Dataset**
The dataset contains annual spending of wholesale distributors across different categories such as fresh products, milk, grocery, etc.

### **Columns**
- `Channel`: Distribution channel (1: Horeca, 2: Retail)
- `Region`: Geographical region (1: Lisbon, 2: Oporto, 3: Other)
- `Fresh`: Annual spending on fresh products.
- `Milk`: Annual spending on milk products.
- `Grocery`: Annual spending on grocery products.
- `Frozen`: Annual spending on frozen products.
- `Detergents_Paper`: Annual spending on detergents and paper products.
- `Delicassen`: Annual spending on delicatessen products.

## **Steps in the Project**
1. **Preprocessing**:
   - Handling missing values and scaling the features using `StandardScaler` for normalization.
2. **Elbow Method**:
   - Determining the optimal number of clusters by plotting inertia (within-cluster sum of squares).
3. **KMeans Clustering**:
   - Applying the KMeans algorithm with the optimal cluster count.
4. **Dimensionality Reduction**:
   - Using PCA to reduce the dataset to 2D for visualization.
5. **Visualization**:
   - Creating visualizations for insights:
     - Elbow plot for optimal clusters.
     - PCA scatter plot for cluster distribution.
     - Heatmap for cluster centers.
     - Pairplot for feature relationships.

## **Results**
- The dataset was clustered into 3 distinct customer segments.
- Visualizations highlight customer spending patterns, aiding in segment-specific strategies.

## **How to Run**
1. Clone the repository:
   ```bash
   git clone https://github.com/your_username/Wholesale-Customer-Clustering.git
