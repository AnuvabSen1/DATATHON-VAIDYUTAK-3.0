# DATATHON

## Problem 1: Online Retail Transactions Analysis

Comprehending consumer behaviour in virtual retail transactions is crucial for e-commerce enterprises to achieve prosperity. Transaction data analysis yields insightful information that may be used to develop plans for many areas of the company. Enhancing client satisfaction is one of transaction analysis's main advantages. Businesses may find pain areas, improve the overall online buying experience, and streamline operations by carefully examining the complete consumer journey. Increased client loyalty and satisfaction are a result of this optimisation. Another important factor that is influenced by transaction insights is personalisation. Businesses may customise marketing campaigns by exploring the unique tastes, purchase history, and browsing behaviours of each consumer. This personalisation includes making product recommendations that are appropriate, creating promotions that are specifically targeted, and providing an enhanced online experience. Transaction analysis helps to support efficient inventory management. Identifying top-selling products and categories allows businesses to optimize stock levels, ensuring popular items are adequately available. Furthermore, placing products strategically according to consumer preferences increases the chance of making a sale. Anticipating and being ready for changes in consumer demand requires an understanding of trends and seasonal patterns. Companies can use these trends to guide their marketing efforts, modifying inventories and providing targeted specials at busy times.

### Dataset Description
This dataset collects vital information for organisations looking to improve their client base understanding by including a variety of factors connected to customer purchase habits. Age, gender, purchase amount, preferred payment methods, frequency of transactions, and feedback ratings are among the aspects that customers can choose from. Data is also provided on the kinds of goods bought, how often they buy, when they like to shop, and how they use special offers. This 4720-record dataset provides a starting point for companies wishing to use data-driven insights to improve decision-making and customer-focused strategy.


### Primary Objective
In this challenge, the objective is to analyze and derive insights from two distinct datasets related to online retail transactions.


### Examples for Analysis
1. **Top-Selling Products and Categories:** - Identify and analyze the top-selling products and categories based on transaction frequency or revenue.
2. **Customer Purchasing Behavior Patterns:** - Investigate trends in customer purchasing behavior based on demographics (age, gender, etc.).
4. **Customer Ratings and Product Satisfaction:** - Analyze customer ratings and feedback to understand overall product satisfaction.
5. **Impact of Discounts or Promotions:** - Explore the impact of discounts or promotions on sales by analyzing transaction data during promotional periods.
6. **Seasonality of Product Purchases:** - Investigate the seasonality of product purchases by analyzing monthly or quarterly sales trends.

### Bonus Challenge
- **Relate Both Datasets:**
  - Identify commonalities and differences in top-selling products and customer behavior between Dataset A and Dataset B.
  - Explore any correlations or patterns that emerge when considering both datasets collectively.

### Dataset Links
- [Dataset Link 1 : https://drive.google.com/file/d/1i6mYpZG_lBk_1Gx-9CuLnwQq9eJ1Jrd_/view?usp=sharing](https://drive.google.com/file/d/1i6mYpZG_lBk_1Gx-9CuLnwQq9eJ1Jrd_/view?usp=sharing)
- [[Dataset Link 2 : https://drive.google.com/file/d/1ikgpwWDYbui1UAC3PFXPAuT_iVvHJWSF/view?usp=sharing](https://drive.google.com/file/d/1ikgpwWDYbui1UAC3PFXPAuT_iVvHJWSF/view?usp=sharing)

---

## Problem 2: Breast Cancer Diagnosis Model

Breast cancer is a significant global health concern, impacting millions of lives every year. Early detection of breast cancer is directly linked to improved treatment outcomes. Timely identification of abnormalities, such as micro-calcifications, allows for early intervention, potentially reducing the severity of the disease and increasing the chances of successful treatment. The detailed annotations provided by expert radiologists in the dataset contribute to the precision of breast cancer diagnosis. Accurate identification and characterization of micro-calcifications enhance the reliability of diagnostic assessments, guiding healthcare professionals in making informed decisions. The dataset includes cases classified into BI-RADS categories, distinguishing between normal (BI-RADS 1), benign (BI-RADS 2), and suspicious (BI-RADS 4-5) conditions. This differentiation is critical for clinicians to prioritize and tailor their approach to patient care based on the severity of the identified abnormalities. Identification of suspicious cases, especially those where biopsy results are available, aids in risk stratification. Understanding the likelihood of malignancy informs healthcare providers about the urgency of further diagnostic procedures and potential treatment strategies.

### Dataset Description
This dataset consists of 100 pairs of mammograms, from two temporally sequential rounds. Specifically, this dataset includes the prior and recent mammograms of CC and MLO view of each patient. This is a complete dataset for the detection and BI-RADS classification of breast micro-calcifications, using digital mammograms. It contains normal (BI-RADS 1), benign (BI-RADS 2), and suspicious (BI-RADS 4-5) cases, and for each mammogram, an image with precise annotation of each individual micro-calcification, by two expert radiologists, is provided. In 32 suspicious cases, the biopsy results are also available.

### Primary Objective
Develop a model utilizing temporally sequential mammogram pairs to accurately diagnose breast cancer and recommend biopsy for suspicious cases (32 cases).

### Examples for Analysis
1. **Temporal Relationship Exploration:**
   - Investigate the temporal relationship between prior and recent mammograms.
2. **Feature Extraction and Model Design:**
   - Extract relevant features from mammogram images to capture micro-calcifications and subtle patterns indicative of cancer.
   - Develop a predictive model to learn and predict breast cancer likelihood.
3. **Biopsy Recommendation:**
   - Incorporate a model with a biopsy recommendation system, specifically focusing on the subset of 32 suspicious cases with available biopsy results.
   - Predict the necessity of biopsy for suspicious cases, aiming for accurate identification.

### Evaluation Criteria
- Utilize standard evaluation metrics such as accuracy, precision, recall, and F1-score to assess the overall performance of the model.

### Presentation and Code
- Share your insights in the form of a PowerPoint presentation.
- Share your code accordingly.
- Marks will be awarded based on the quality of the presentation.

### Dataset Link
- [Breast Cancer Dataset](https://zenodo.org/records/7969411)
