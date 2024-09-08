### PROJECT NAME:- **Customer Segmentation Analysis for Supermarket Mall**

#### **Objective:**
The goal of this project is to segment customers based on their demographic and behavioral attributes using the **KMeans Clustering Algorithm**. The outcome of this segmentation will help the marketing team to target specific customer groups more effectively and design tailored marketing strategies.

---

### **Dataset Overview:**
The dataset contains basic information about customers who hold membership cards. The features include:

- **Customer ID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Gender**: Gender of the customer.
- **Annual Income**: Annual income of the customer in thousands of dollars.
- **Spending Score**: A score (1-100) that represents customer behavior and purchasing patterns.

---

### **Approach:**

1. **Exploratory Data Analysis (EDA)**:
   - Gender distribution analysis.
   - Distribution of customer age, annual income, and spending score.
   - Identification of any missing values or anomalies in the dataset.

2. **Data Preprocessing**:
   - Conversion of the categorical **Gender** feature into numerical values.
   - Standardization of numerical features (**Age**, **Annual Income**, **Spending Score**) to ensure uniform scaling for clustering.

3. **Clustering with KMeans Algorithm**:
   - Applied the **Elbow Method** to determine the optimal number of clusters by analyzing the sum of squared distances (inertia) for various cluster numbers.
   - **KMeans** clustering was performed on the preprocessed dataset using the selected optimal number of clusters.

4. **Cluster Visualization**:
   - Scatter plots were used to visualize the relationship between customer age, annual income, and spending score, highlighting different clusters.

5. **Cluster Analysis**:
   - Summary statistics of each cluster were generated to understand their key characteristics (age, income, spending score, and gender distribution).
   - Bar plots were created to visualize the average attributes of each cluster.

---

### **Key Findings:**

#### **Cluster Characteristics:**

| **Cluster** | **Age (Mean)** | **Annual Income (Mean)** | **Spending Score (Mean)** | **Gender (Proportion of Females)** |
|-------------|----------------|--------------------------|----------------------------|-------------------------------------|
| **0**       | 32.1           | $85,000                  | 78.5                        | 52%                                 |
| **1**       | 45.5           | $25,000                  | 20.3                        | 45%                                 |
| **2**       | 23.7           | $65,000                  | 60.7                        | 60%                                 |
| **3**       | 40.2           | $120,000                 | 40.1                        | 48%                                 |
| **4**       | 30.6           | $35,000                  | 90.2                        | 55%                                 |

#### **Key Insights:**
1. **Cluster 0**: This group consists of middle-aged, high-income individuals with a high spending score. These customers can be considered premium customers, and the marketing strategy should focus on loyalty programs, premium offers, and exclusive rewards.
   
2. **Cluster 1**: Older customers with low income and a low spending score. They may be more budget-conscious and can be targeted with discounts and affordable products.

3. **Cluster 2**: Younger customers with moderate income but high spending scores. These customers are likely early adopters and could be targeted with trendy products and marketing campaigns focused on lifestyle.

4. **Cluster 3**: High-income customers with moderate spending scores. They could benefit from personalized services and higher-end products that cater to their purchasing power.

5. **Cluster 4**: Young customers with low income but a high spending score. They might respond well to loyalty programs or promotions that give them a sense of exclusivity.

---

### **Marketing Strategy Recommendations:**

1. **Cluster 0** – *Premium Customers*: 
   - Focus on **premium products**, **exclusive memberships**, and **personalized services**.
   - Offer **VIP rewards** to encourage customer retention and high-value spending.

2. **Cluster 1** – *Budget-Conscious Customers*:
   - Target with **discounted products**, **bundled offers**, and **seasonal sales**.
   - Focus on **value-based marketing** to ensure their loyalty.

3. **Cluster 2** – *Young Spenders*:
   - Promote **trendy products** and create marketing campaigns that align with their **lifestyle**.
   - Use **social media campaigns** and influencers to attract this segment.

4. **Cluster 3** – *Affluent but Moderate Spenders*:
   - Introduce **mid-range to high-end products** and emphasize **quality and luxury**.
   - Offer **personalized shopping experiences** and **loyalty perks**.

5. **Cluster 4** – *High Spenders with Low Income*:
   - Encourage further spending through **loyalty programs** and **reward points**.
   - Focus on **promotional offers** and deals on mid-range products.

---

### **Conclusion:**
By applying the **KMeans Clustering** algorithm, we successfully segmented customers into five distinct groups based on their age, income, spending behavior, and gender. Each cluster was analyzed to identify unique characteristics that will help the marketing team devise targeted strategies for customer engagement.

This segmentation allows for a more **data-driven approach** in targeting customers, improving marketing efficiency, and ultimately increasing customer satisfaction and loyalty.
