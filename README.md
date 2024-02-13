# Customer-segmentation-using-KMeans

**Project Overview: Customer Data Segmentation**

**1. Introduction:**
   As the owner of a supermarket mall, understanding customer behavior and preferences is crucial for effective marketing strategies and personalized customer experiences. Utilizing membership card data, we have access to essential customer information such as Customer ID, age, gender, annual income, and spending score. The spending score is a metric assigned to customers based on predefined parameters reflecting their purchasing behavior. 
 Dataset : https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python/data

**2. Preprocessing:**
   - Initial data inspection reveals no missing values, enabling us to proceed with segmentation.
   - We analyze the distribution of gender within our dataset and explore its relationship with other features.

**3. Data Visualization:**
   - Through plotting, we observe distinct clusters where female customers are represented by orange and male customers by blue.
     ![image](https://github.com/sudikshaacharya1/Customer-segmentation-using-KMeans/assets/138321124/d544a9f5-4b18-4a33-98b1-fad1ed162376)

   - We proceed to select key features for segmentation: annual income and spending score, as well as age and spending score.

**4. Feature Selection 1: Annual Income and Spending Group:**
   - We slice the dataset to isolate annual income and spending score.
   - Utilizing the elbow method, we determine the optimal number of clusters to be 5, as there is no significant drop in within-cluster sum of squares (WCSS) beyond this point.
     ![image](https://github.com/sudikshaacharya1/Customer-segmentation-using-KMeans/assets/138321124/3fc4e35e-96c4-4950-adbc-e1bf82ac0c56)
   - Visualizing the clusters based on their assigned numbers, we observe significant clustering of customers based on their income and spending behavior.
     ![image](https://github.com/sudikshaacharya1/Customer-segmentation-using-KMeans/assets/138321124/4565bcf4-3aee-4cb0-a67f-5e1b5d68d7a9)


**5. Feature Selection 2: Age and Spending Group:**
   - Similar to the previous step, we slice the dataset to isolate age and spending score.
   - Employing the elbow method, we identify 4 as the optimal number of clusters.
     ![image](https://github.com/sudikshaacharya1/Customer-segmentation-using-KMeans/assets/138321124/6cf8471f-c09d-4961-aff4-35bef3fd0618)
   - Visualizing these clusters, we uncover distinct patterns relating age to spending behavior.
     ![image](https://github.com/sudikshaacharya1/Customer-segmentation-using-KMeans/assets/138321124/808f0d2a-148d-4776-bd0c-8fe421f7a46e)


**6. Interpretation:**
   - The segmentation based on both annual income and age against spending score reveals meaningful insights into customer behavior.
   - By understanding these clusters, we can tailor marketing strategies and promotions to effectively target different customer segments.
   - This segmentation approach empowers the supermarket mall to enhance customer satisfaction, loyalty, and overall business performance.

**7. Conclusion:**
   Through customer data segmentation, we gain valuable insights into the diverse preferences and behaviors of our customer base. By leveraging these insights, we can implement targeted marketing strategies and enhance customer experiences, ultimately driving business growth and success.
