

#  Apple Stock Analysis Project

 **By:** Ikram Mansar & Phuong Le Linh 
 
 **School:** Rennes School of Business
 
 **Course:** Programming & Statistics Project
 
 **Topic:** Exploring Apple Inc. Stock Data


##  About Our Project

In this project, we worked together to explore **Apple Inc.’s stock performance** using Python. Our goal was to understand how Apple’s daily stock returns change over time and see if we could find any patterns or factors that influence them.

We combined what we learned from **programming** and **statistics** to clean, analyze, and model real financial data.



##  Research Question

 How do Apple’s daily stock returns behave over time, and can we find patterns or factors that explain their changes?



##  What We Did

1. **Data Loading & Cleaning**

   * We used pandas to load Apple’s stock data and clean it.
   * We checked for missing values and fixed the date format for time analysis.

2. **Feature Engineering**

   * We calculated *Daily Return* = (Close - Open) / Open × 100.
   * We also created *Moving Averages* to smooth out trends.

3. **Exploratory Data Analysis (EDA)**

   * We plotted Apple’s *Closing Price* and *Volume* over time.
   * We looked at the distribution of daily returns using histograms and density plots.

4. **Descriptive Statistics & Normality Test**

   * We calculated the mean, median, standard deviation, etc.
   * We used the Shapiro–Wilk test to check if returns were normally distributed (they weren’t!).

5. **Hypothesis Testing**

   * We compared returns in bullish (good) years and bearish (bad) years using the Mann–Whitney U test.
   * The result showed no significant difference between them.

6. **Regression Analysis**

   * We used Linear Regression to predict daily returns and Logistic Regression to predict high-return days.
   * Results showed that predicting returns isn’t easy returns depend on many factors beyond just volume and previous return.

7. **Random Forest Model**

   * We tried a Random Forest classifier to see which features best predict high-return days.
   * The model confirmed that predicting daily returns remains quite complex.



##  What We Found

* Apple’s stock returns **are not normally distributed**.
* **No major difference** was found between bullish and bearish years.
* **Machine learning models** like Regression and Random Forest had low prediction power meaning stock returns are influenced by many unpredictable market factors.


##  Tools We Used

* **Python Libraries:** pandas, numpy, matplotlib, seaborn, scipy, sklearn, statsmodels
* **Platform:** Google Colab
* **Version Control:** GitHub



##  What We Learned

Through this project, we improved our skills in both **programming** and **statistics**.
We learned how to clean and analyze real-world data, visualize trends, run hypothesis tests, and apply predictive models.
It was a great experience connecting both fields to understand financial data in a practical way!



