**UC Berkeley - AI/ML Practical Application 1**

**Problem Statement : Will the customer accept the coupon?**

**Project Overview:**
The main goal of this project was to use charts and statistics/probability capabilities to understand the difference between customers who accepted a driving coupon and those who didn’t.

The project was done using Python, with the help of the following libraries: pandas, seaborn, matplotlib, numpy and autoviz.
All the details—like the code, graphs, notes, and findings—are available in the Jupyter Notebook available in the code repo.

**Exploratory Data Analysis(EDA):**
**Data Quality Issues Identified:**
**Missing Data:**
About 99% of the 'car' column is empty, so it doesn't provide useful information for the analysis. Other columns only have a small number of missing values (less than 2%), which won’t have a big impact on the overall results. Therefore, the ‘car’ column was removed from the dataset, further while analyzing Bar coupon related data.

**Duplicate Data:**
There are 74 duplicate rows in the dataset. From the data overview, we can assume that this was a surey data and hence, it's normal to have some duplicate responses. We kept the duplicates as the count of duplicates is almost neglibile and wont create much outliers.

**Summary of Findings**

**Overall:**
People used coupons in about 57 out of every 100 cases.

**Bar Coupons:**
* Bar coupons were used 41% of the time overall.
* People who go to bars 3 times or less a month used the coupon 37% of the time.
* People who go to bars more than 3 times a month used it 76% of the time.
* Drivers older than 25 who go to bars more than once a month used the coupon 70% of the time.
* Drivers who go to bars often, have no kids in the car, and don’t work in farming, fishing, or forestry used it 71% of the time.
* Drivers who go to bars often, have no kids in the car, and are not widowed also used it 71% of the time.
* Drivers under 30 who go to bars often used the coupon 72% of the time.
* People who eat at cheap restaurants more than 4 times a month and earn less than $50K a year used the bar coupon 45% of the time.
  
**Hypotheses**

Based on what we observed, here are some ideas about why certain drivers accepted bar coupons:

**Frequent Bar Visitors**
Drivers who go to bars often—especially more than 3 times a month—are much more likely to use bar coupons. This may be because regular visitors see more value in the discount.

**Younger Drivers**
Drivers under 30 are more likely to accept bar coupons. This could be because younger people are more interested in going out and are more open to using discounts for social activities.

**Marital Status and Jobs**
Drivers who are not widowed and who don’t work in farming, fishing, or forestry are more likely to take bar coupons. This may be related to lifestyle differences—some people may have more social time or different interests based on their job or relationship status.

**Spending Habits and Income**
Drivers who often eat at cheaper restaurants and earn less than $50,000 a year also show unique patterns in using bar coupons. This suggests that how much people earn and how they spend money on food can affect how useful they find the coupons.

**Other Drivers**
Drivers outside of these groups are less likely to accept bar coupons. This shows that certain behaviors and personal traits—like not going to bars often—play a big role in whether someone uses a coupon.

**Recommended Next Steps:**
**Summary: Recommended Actions to Improve Coupon Campaigns**
Based on the analysis of drivers who accept bar coupons and those who turn down Carry Out & Take Away coupons, here are some practical steps to better understand the data and improve future campaigns:

**Detailed Group Analysis**
Take a closer look at smaller groups within the data by combining factors like time of day, weather, and location. This will help identify patterns in who is more likely to accept coupons.

**Build Predictive Models**
Create models that can predict whether someone will use a coupon based on their background, behavior, and other outside factors. This helps in planning more effective campaigns.

**Test Different Approaches (A/B Testing)**
Try out different coupon designs, offers, and messages to see what works best for different types of drivers. This will help make the campaigns more effective.

**Measure Business Impact**
Analyze how these coupon campaigns affect things like sales, customer loyalty, and return visits. This will help decide if the investment is worth it and guide where to spend the marketing budget.

**Look at Competitors**
Research how other companies are using coupons. This can provide ideas and help your campaigns stand out.

**Use Multiple Marketing Channels**
Combine coupon campaigns with other ways of reaching customers, like social media, email, and mobile apps. Using multiple channels can increase visibility and success.

