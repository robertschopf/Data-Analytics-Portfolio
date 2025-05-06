#  🧨 Robert Schopf - Data-Analytics-Portfolio

👋 Hi, I'm Robert! I've transitioned from operations and sports management to data analysis because I believe data has the power to transform businesses. I leverage SQL, Python, Tableau, and Google Sheets to extract data-driven insights and create visualizations that improve business value and operating procedures. 

Whether working independently or in teams, I focus on impactful analyses and data storytelling that drive these positive changes. On this GitHub, you’ll find some of my data analysis projects. Let’s explore data together!

---

## 👨🏻‍💻 About me

🎓 Trained as a data analyst, bridging my background in operations and sports management with a passion for data-driven solutions. I combine my operational experience with hands-on expertise in data cleaning, transformation, and visualization to solve real-world problems. 

I'm always interested in collaborating on new projects and expanding my skillset.  My personal projects focus on pattern recognition and dashboard creation, empowering others to use data more effectively. I thrive on challenges and enjoy sharing insights that contribute to better business decisions.

---

## 🗂️ Table of Contents
* [About Me]()
* * [Portfolio Projects]()
  * 🦄 [1. Unicorn Company: Data Exploration & Insights (SQL + Tableau + Google Sheets)](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#-1-unicorn-company-data-exploration--insights-sql--tableau--google-sheets)
  * 🚗 [2. Car Data Analysis (Python)](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#-2-car-data-analysis-python)
  * 🏎️ [3. Vehicle Classification based on Silhouette Features (Supervised Learning with Python)](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#%EF%B8%8F-3-vehicle-classification-based-on-silhouette-features-supervised-learning-with-python)
  * 🚗 [4. Vehicle Segmentation and Classification using Unsupervised Learning (Python)](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#-4-vehicle-segmentation-and-classification-using-unsupervised-learning-python)
  * ✈️ [5. TravelTide - MasteryProject](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#%EF%B8%8F-3-traveltide-development-of-a-personalized-rewards-program)
* [Education](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#-education)
* [Certificates](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#-certificates)
* [Contact](https://github.com/robertschopf/Data-Analytics-Portfolio?tab=readme-ov-file#-contact)

---

## 📊 Portfolio Projects

### 🦄 [**1. Unicorn Company: Data Exploration & Insights (SQL + Tableau + Google Sheets)**](https://github.com/robertschopf/unicorn_project)

**Goal:**  
To perform in-depth data exploration using SQL, conduct data cleaning and transformation using Google Sheets, build an executive-level dashboard with Tableau, and generate actionable business recommendations for Unicorn based on the insights gained.

**Description:**  
The project involved examining Unicorn Company's sales, profit and customer data using SQL queries and converting the findings into an actionable Tableau dashboard. My analysis focused primarily on the KPI's of sales and profit for each category and segment

**Part 1:** Data Exploration with SQL
* Leveraged SQL to analyze Unicorn's database, focusing on sales, revenue, profit, and customer behavior. 

* Cleaned and joined tables such as 'customers,' 'orders,' and 'order_details.' Performed aggregations and generated rankings to identify top-performing products, categories, regions, and customer segments, revealing key trends and relationships within the data.

**Part 2:** Analysis with Google Sheets
* Created calculated columns (e.g., price per unit, profit margin) and utilized pivot tables to analyze data by category, segment, and region. Employed conditional formatting to highlight key findings and trends

**Part 3:** Insights & Dashboard with Tableau
* Developed a Tableau dashboard to visualize key insights and trends, empowering data-driven business decision-making within the company.

**Skills:**
* **SQL:** Data querying, joins, DML/DQL operations, subqueries, aggregations
* **Data Manipulation:** Data cleaning, filtering, transformation, and validation
* **Data Visualization:** Tableau for dashboard creation, interactive visualizations, and exploration
* **Business Analysis:** Data analysis, trend identification, KPI analysis, and development of actionable business recommendations

**Technology:** 
PostgreSQL, Google-Sheets, Tableau

**Key Insights:**
* Identification of the regions, categories, segments and products with the highest sales and best performing
* Presentation of potential market opportunities and specialization options by markt categories
* Recommendation of bundling the marketing budget and pricing structure linked to the discount strategy

📈 **Results:**
* [Tableau Public Dashboard](https://public.tableau.com/views/Project_Unicorn/UnicornDashboardbyCategoryandSegment?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
* [Google-Sheets](https://docs.google.com/spreadsheets/d/12tABKnn91MjVXZ7KtPKL8IDQuw5TvX9Fu8-BQ3351_w/edit?usp=sharing) 
* [SQL Queries](https://github.com/robertschopf/unicorn_project/blob/main/unicorn_project.sql)

---

### 🚗 [**2. Car Data Analysis (Python)**](https://github.com/robertschopf/car_data_analysis)

**Goal:**  
Gain deep insights by cleaning, transforming and analyzing the vehicle dataset to uncover correlations between vehicle characteristics and market behavior.

**Description:**  
This project utilized Python to analyze a car dataset, focusing on data cleaning, feature engineering, and exploratory analysis. The dataset included details such as car make, model, engine specifications, fuel type, and price. The goal was to identify key trends and relationships between vehicle characteristics and market factors.

**Key Tasks:**
* Cleaned the data by addressing missing values, ensuring data type consistency and standardizing text formats. Filtered the dataset to include only cars produced from 1995 onwards.
* Created new features, such as "Total MPG" and "Price per Horsepower," to gain deeper insights into vehicle performance and value
* EDA includes the calculation of descriptive statistics, group analyses and the creation of various diagrams to identify and visualize patterns, trends and relationships between market size, car prices, engine HP or consumption.

**Skills:**
* Loading, cleaning, and transforming data  (with Pandas & NumPy)
* Conducting descriptive statistics
* correlation analysis 
* generating informative visualizations (with Matplotlib & Seaborn)

**Technology:** 
Python with libarys like Pandas, NumPy, Matplotlib, Seaborn

**Key Insights:**
* Higher engine power typically correlates with higher MSRP
* Larger vehicles typically have higher MSRPs than smaller vehicles
* Higher power leads to higher fuel economy
* Direct shift transmissions typically offer better fuel efficiency than other transmission types
* There is little correlation between MSRP and popularity

📈 **Results:**
* [Google Colabs Notebook](https://colab.research.google.com/drive/1867ErT9_cWf1LzrVDklDDi1wnbPa-sc4?usp=sharing)

---

### 🏎️ [**3. Vehicle Classification based on Silhouette Features (Supervised Learning with Python)**]()

**Goal:**
Development of a classification model to distinguish between three different vehicle types (bus, van, car) based on their silhouette features for the "Prospect Auto" car repair shop chain.

**Description:**
This project employed a supervised learning approach to train a model capable of classifying vehicles based on geometric features extracted from their silhouettes. The dataset contains numerical features derived from the silhouettes of buses (double-decker), vans (Chevrolet), and cars (Saab 9000 or Opel Manta). The objective was to develop an accurate classification model that reliably differentiates the three vehicle types, acknowledging that distinguishing between the two car models might present a greater challenge.

**Key Steps:**
* **Data Import and Exploration:**
    * Loading the dataset and conducting initial exploratory data analysis (EDA) to gain insights into the data structure, distributions, and potential relationships between the features and the target variable ('class').
    * Visual and numerical analysis of the data to identify any anomalies, missing values, or potential issues.

* **Data Preparation:**
    * Normalizing or standardizing the numerical features to ensure all features contribute equally to the model.
    * Splitting the dataset into training and testing sets to train the model on a portion of the data and evaluate its performance on unseen data.

* **Model Development and Training:**
    * Application of various supervised learning classification algorithms, such as Support Vector Machines (SVM), Random Forests, and Logistic Regression.
    * Training the selected models using the training dataset.
    * Potential execution of hyperparameter tuning to optimize the performance of the models.

* **Model Evaluation:**
    * Selection of appropriate metrics to evaluate model performance (e.g., Accuracy, Precision, Recall, F1-Score, Confusion Matrix).
    * Evaluating the trained models using the test dataset to assess their generalization ability.

* **Results and Conclusions:**
    * Analyzing the evaluation results and comparing the performance of different models.
    * Discussing the strengths and weaknesses of the best-performing model and its suitability for classifying vehicle silhouettes for "Prospect Auto."

**Skills:**
* **Supervised Learning:** Classification
* **Data Preparation:** Normalization, Standardization, Train-Test Split
* **Explorative Datenanalyse (EDA):** Visualization and descriptive statistics
* **Model Development and Training:** Application of various classification algorithms
* **Model Evaluation:** Selection and interpretation of classification metrics
* **Python Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

**Technology:**
* Google Colab
+ Python with libarys like Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

**Key Insights:**
* Features like 'compactness', 'circularity', and 'elongatedness' showed significant discriminatory power between buses and the other vehicle types.
* Random Forest and Support Vector Machine models achieved high accuracy in classifying the vehicles.
* Distinguishing between 'car' and 'van' proved to be slightly more challenging than identifying 'bus'.

**📈 Results:**
* [Google Colabs Notebook](https://colab.research.google.com/drive/1A2FYZacpN4Ck65cxiW-7rqkyu40NLjad?usp=sharing)

---

### 🚗 [**4. Vehicle Segmentation and Classification using Unsupervised Learning (Python)**]()

**Goal:** Application of Unsupervised Learning techniques to segment vehicle data based on their silhouette features and subsequent evaluation of whether this segmentation can be used to solve the classification problem for "Prospect Auto".

**Description:** This project utilized the same dataset of silhouette features from buses, vans, and cars as the previous Supervised Learning project. The aim was to identify patterns and natural groupings (clusters) within the data through Unsupervised Learning, without using the actual vehicle types (the 'class' column) during training. Subsequently, the project investigated the extent to which these automatically discovered clusters align with the actual vehicle types and whether this approach is suitable for vehicle classification.

**Key Steps:**
* **Data Import and Preparation:**
    * Loading the dataset.
    * Normalizing or standardizing the numerical features to ensure all features equally influence the clustering algorithm.
    * Splitting the dataset into training and testing sets (although pure Unsupervised Learning doesn't have a training set in the same sense, a split can be useful for later evaluation of the found clusters).

* **Dimensionality Reduction (PCA):**
    * Applying Principal Component Analysis (PCA) to reduce the original 18 dimensions to a lower number while preserving a significant portion of the data's variance.
    * Evaluating the efficiency of dimensionality reduction and the number of principal components to retain.

* **Clustering:**
    * Applying one or more Unsupervised Learning clustering algorithms, such as k-Means and potentially DBSCAN.
    * Training the clustering model on the prepared data (possibly after dimensionality reduction).
    * Identifying the resulting clusters.

* **Evaluation:**
    * Using appropriate metrics to evaluate the clustering results (e.g., Silhouette Coefficient, Davies-Bouldin Index) and to measure the agreement between the found clusters and the actual vehicle types (e.g., Adjusted Rand Index, Normalized Mutual Information).

* **Comparison with Supervised Learning:**
    * Comparing the performance of the Unsupervised Learning approach (in terms of vehicle classification) with the results of the previously developed Supervised Learning model.
    * Concluding which approach is more suitable for this specific problem.

**Skills:**
* **Unsupervised Learning:** Clustering (e.g., k-Means, DBSCAN), Dimensionality Reduction (PCA)
* **Data Preparation:** Normalization, Standardization
* **Evaluation of Clustering Results:** Silhouette Coefficient, Adjusted Rand Index, etc.
* **Python Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

**Technology:**
* Google Colab
+ Python with libarys like Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

**Key Insights:**
* The k-Means algorithm identified three distinct clusters in the vehicle data.
* PCA effectively reduced the dimensionality to around 5-7 principal components while retaining over 80% of the variance.
* While the clusters showed some correlation with the actual vehicle types, the overlap indicated that unsupervised clustering alone might not be as accurate for classification as the supervised learning approach. The Adjusted Rand Index showed a moderate level of agreement.
* Supervised learning, leveraging the labeled data, achieved significantly higher accuracy in classifying the vehicles compared to the unsupervised clustering approach.

**📈 Results:**
* [Google Colabs Notebook](https://colab.research.google.com/drive/1EABV4jp1dG4RxKrkk-lXS52O7f1pIXlk?usp=sharing)

---

### ✈️ [**5. TravelTide: Development of a Personalized Rewards Program**](https://github.com/robertschopf/masteryProject_traveltide)

**Goal:**
* Development of a personalized customer retention strategy through a rewards program to strengthen customer loyalty, encourage repeat customers, and ultimately increase customer lifetime value on the TravelTide platform.

**Description:**
* TravelTide is an emerging e-booking startup distinguished by its advanced data aggregation and search technology.
* The project focuses on analyzing customer data to develop a rewards program tailored to individual customer needs.
* This involves identifying customer segments and assigning the most relevant rewards to each segment to maximize the program's effectiveness.

**Key Tasks:**
* Data exploration and preparation (including cleaning and transformation)
* Customer segmentation (based on behavior and demographics)
* Analysis of reward preferences (to identify appealing perks)
* Development of a reward assignment model (for personalized offers)
* Validation of results (to ensure accuracy and effectiveness)

**Skills:**
* Data analysis
* Customer segmentation
* Rewards program development
* Data-driven decision-making

**Technology:**
* Tableau (for visualizing analysis results)
* Google Colab (for data analysis and model development using Python libraries like Pandas and scikit-learn)

**Key Insights:**
* Identification of customer segments with varying reward preferences (e.g., price-sensitive customers prefer flight discounts, loyal customers value hotel benefits like free upgrades)
* Development of a model for personalized reward assignment to increase program appeal (e.g., assigning 'no cancellation fees' to customers with a history of frequent cancellations)

**📈 Results:**
* [Tableau Public Dashboard](https://public.tableau.com/app/profile/robert.schopf/viz/MasterProject-TravelTide-RS/TravelTideRewardsProgramLeveragingCustomerDataforPersonalizedPerks)
* [Tableau Public Presentation Dashboard](https://public.tableau.com/app/profile/robert.schopf/viz/MasterProject-Presentation-TravelTide-RS/TravelTidepresentation)
* [Google Colabs Notebook](https://colab.research.google.com/drive/16pukAUnjZQ2kKL2zRD7BLIN_jfxlfwkL?usp=sharing)

---

## 🎓 Education

* Data Analytics at Masterschool (still in Progress)

---

## 📜 Certificates

* Masterschool

* DataCamp
  * [Orientation Course - Data Analytics - Track](https://drive.google.com/file/d/11vkK_B9csKjn_FOyv7v_Z_UCsI_KQMZg/view?usp=drive_link)
  * [Understanding Data Topics - Track](https://drive.google.com/file/d/1qvhcz8sTITllCsqOjLB99vNb-H-P51td/view?usp=drive_link)
  * [Google Sheets Fundamentals - Track](https://drive.google.com/file/d/1LdMxsRnTFQ36m7mlNAzBw08siFk2V4P8/view?usp=drive_link)
  * [Spreadsheets and Tableau- Track](https://drive.google.com/file/d/1IW7ZquCQw844ZLEabwcVej5Lzf_3-Wm2/view?usp=drive_link)
  * [Tableau Fundamentals- Track](https://drive.google.com/file/d/1mVSNAcL0POAp2Y2Insk8YFzk5WP7oz2j/view?usp=drive_link)
  * [SQL Fundamentals - Track](https://drive.google.com/file/d/1Bj1DhmFjzjXqNwrwYNeo4uz626IWGfSi/view?usp=drive_link)

* Cousera
  * Python for Data Analysis
---

## 📬 Contact
Please don't hesitate to contact me on [LinkedIn](http://www.linkedin.com/in/robertschopf) or via email to discuss potential projects, opportunities or collaborations.

---

I hope you find this project portfolio to be both inspiring and insightful. 🌟
