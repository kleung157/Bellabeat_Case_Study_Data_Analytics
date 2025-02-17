# Bellabeat Case Study: 
## How Can A Wellness Technology Company Play it Smart?

![bellabeat logo](./bellabeat_logo.png)

##### Author: Kevin Leung
##### Date: 2025-01-27

#### Background:
Founded in 2013 by artist Urška Sršen and mathematician Sando Mur, Bellabeat is a health and wellness technology company that seeks to inform, inspire, and empower women to make health-conscious decisions. Bellabeat manufactures smart devices that can track an individual’s activity, sleep, stress, mindfulness, and reproductive health habits. Combined with their companion Bellabeat app and subscription-based membership model, these products deliver personalized data and guidance to meet a user’s current lifestyle and desired goals. More recently in 2016, Bellabeat released multiple new products (Leaf, Time, and Spring) and expanded its’ offices around the world. Bellabeat products are available through a number of online retailers and displayed extensively in digital marketing platforms such as Google, Facebook, Instagram, Twitter, YouTube, etc. 

#### Business Task:
Discover opportunities for growth in current and future markets by using non-Bellabeat smart device usage data to identify trends compatible with Bellabeat products and deliver insights that can drive strategical innovation for Bellabeat to have a greater global presence.

#### Dashboard:
![bellabeat_dashboard](./bellabeat_dashboard.png)

#### Recommendations:
**What are some trends in smart device usage? How could these trends apply to Bellabeat customers?**

- Smart devices show a significant emphasis on tracking metrics based on number of observations that involve being active including heart rate, steps, distance, calories burned, energy expenditure (METs), and intensity. Less emphasis on non-active metrics like sleep and weight tracking.

- Under CDC daily recommendations, FitBit users on average successfully met the target daily goals for calories burned (2000-3000 men, 1600-2400 women calories) and active minutes (>=30 minutes). However, users on average fell short of meeting the total steps (8000-10000 steps), heart rate (>=100 value), sleep (>=7 hours) and weight criteria (<18.5 under, 18.5-24.9 normal, > 25 overweight bmi).

- Users spend 18% of their daily time active and 82% sedentary. Approximately 1/5 active, and 4/5 sedentary.

- Users on average are overweight with a BMI of 25.37, which may not represent the sample size as that is 0.37 bmi off of being normal under CDC recommendations.

- Users spend on a daily average 7 ½ hours in bed, 6.98 hours sleeping which barely meets the minimum by CDC of at least 7 hours. Users on a minute average spend more time in sleep stage 1, lighter sleep. According to the CDC, more time should be focused in stage 3 where deep sleep and non-rapid eye movement occurs.

- Users show the greatest overall input for active metrics on Tuesdays. For passive metrics like sleep and weight, Wednesdays shows the most input.

- Users show the greatest total hourly input in active metrics like calories burned, intensity, and steps between the hours of 12-2PM and 5-7PM.

- If we look at specific trends on a daily, hourly, and minute input basis to understand a user's daily activity, sleep and stress, then looking at variables that have correlation coefficients with a very strong relationship would be most recommended. Tracking these specific fields on smart devices would be to the immediate benefit of Bellabeat users and can be reliably explored further.

**Very strong correlation (0.8 - 1.0)**

total_steps / total_distance (daily) – 0.986

total_time_in_bed / total_minutes_asleep (daily) – 0.930

calories / total_intensity (hourly) – 0.897

calories / total_steps (hourly) – 0.808

total_intensity / total_steps (hourly) – 0.892

calories / total_intensity (minute) – 0.894

calories / mets (minute) – 0.954

calories / total_steps (minute) – 0.824

total_intensity / mets (minute) – 0.940

total_intensity / total_steps (minute) – 0.808

mets / total_steps (minute) – 0.884

**How could these trends help influence Bellabeat marketing strategy?**

- Campaign with a health organization like the CDC for educating users on what daily metrics can contribute to a healthy, active lifestyle and encourage them to set goals on the Bellabeat app.

- Smart device active metrics are passively tracked on a frequent basis. Non-active metrics like sleep and weight could have a notification on a user's device or an incentive on the Bellabeat app for users to manually input data more frequently.

- Target middle of the week (Tuesday/Wednesday) and the hours between 12-2pm, 5-7pm for user notifications and incentives on the Bellabeat app.

- Users should be able to see a more complete daily end of the day total that is a passive sum of hourly or minute metrics. Daily active metrics on the Bellabeat app need to be tracked more consistently on top of existing hourly and minute metrics to establish a better understanding of the relationship between daily active metrics and daily passive metrics such as sleep and weight.
