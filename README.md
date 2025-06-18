# Row Health Marketing Insights - Project Overview

## Project Goal: 

To examine Row Health health campaigns created in 2019 and compare them to-date in one dashboard. The main metrics are based on marketing metrics. The focus being on signups, claims, and impressions. These metrics will be used for budget allocation across future marketing campaigns.


## Background

Row Health is a medical insurance company that was founded in 2016. 2019 was when Row Health launched their marketing campaigns that include categories such as wellness tips, affordability of plans, and preventative care. There are 4 different plans bronze, silver, gold, and platinum. Each plan comes with different premiums and claim coverage rates. 


## Dataset Structure

The dataset contains three tables. Metadata found include information about campaigns, signups, and user demographics. Customer claim information is connected via customer id. 

![Image](https://github.com/user-attachments/assets/cf932e7b-87e5-47fa-95b9-5fb1a17fdcdf)

## Insights Summary 

**For campaign evaluation performance, we focused on these north star metrics:**
- **Signup Rate:** The percent of people who see a campaign and sign up for a Row Health Plan.
- **Cost per Signup:** The average dollars spent to acquire a signup from each campaign.
- **Click Through Rate:** The percent of people who see a campaign and click on the associated link.

#### Signup Rate
- Across campaign categories, Health for All had the best performing signup rate (2.08%). They also had the second highest number of signups (3.5k).
- #Healthyliving had 3.7K signups but fell through with their signup rate at a low of 0.27%.
- Health for All is an outlier in its campaign type of Health Awareness. The second highest performing campaign type only has a 0.02% signup rate.

#### Click through Rate:
- Health for All had the highest CTR at 25.48% and Benefits update 22.17%. Health for All noticeably has the lowest amount of impressions at 170K.
- Golden Years Security had the lowest CTR at 1.41%. An investigation should be done to see why CTR rate is so low when impressions are not considerably low.
- Family Coverage Plan does not contain any CTR data or Cost per Click data, investigate to see if there is missing data or issues with data collection.

#### Cost per Signup
- Golden Year Security in addition to a low CTR also has a high cost per signup as a result. The cps is $176.73 while the average is $29.04. An investigation should be conducted into Golden Year Security to either discontinue or cut costs.
- Coverage matters has the lowest cost per sign up at $0.65. A key note is that CTR is only at 10.43% so this campaign has very high retention once customers click and learn about the campaign.

## Recommendations
- **Health for All:** Reallocate the budget from Golden Years Security to Health for All. Golden Years Security runs too high of a cost for the amount of signups. Reallocating to a better performing campaign can bring in more customer signups.
- **Compare Health Coverage:** We can also reallocate budget from this campaign over to benefits update. Compare Health Coverage has the highest cost but ranks in the middle for CTR and impressions. The increase of spending to a better performing campaign could be better for the marginal increase.
- **Post Pandemic Spending:** Looking at the signup trends after COVID-19, there is a significant drop signups. This affects all campaigns so there should be a decrease in all spending for health campaigns.


## Dashboard 
![Image](https://github.com/user-attachments/assets/305f298b-a10b-4a48-a09a-a114b2feaf57)







