**Lines 101-140:**

Gender:
Male patients had a wider range of air forcefully exhaled in 1 second in comparison to female patients. Their minimums within the dataset were very similar, but ultimately, male patients had a higher maximum, inhaling close to 5 liters of air while the maximum female patient inhaled only 3.5 liters at most.

Race:
White patients had a wider range of air forcefully exhaled compared to black patients. However, white and black patients had a very similar interquartile range (with white patients being slightly higher) and median volume, both being close to about 2 liters.

Smoking Status:
Current smokers and former smokers had very similar interquartile range of air forcefully exhaled. The median volume for current and former smokers were both around 2 liters (current smokers being slightly higher). The disparity between the minimum and maximum value for former smokers was higher than the disparity for current smokers.

Emphysema:
This boxplot showed the largest difference between its two categories in comparison to the other graphs. Those who reported to have emphysema had an interquartile range of approximately 1.75 to 2.75 liters, while those who did not have emphysema only had a interquartile range of approximately of 0.9 to 1.9 liters. The maximum value for those with emphysema was over 5 liters of air exhaled, while patients without emphysema had a maximum of less than 4.5 liters. They had similar minimum values, both being less than half a liter. The results of this graph were a surprise, as I expected those with emphysema to exhale significantly less air due to problems of shortness with breath.

Asthma:
There was a large difference in air exhaled for people in the asthma category. The interquartile range for those with asthma was greater than the interquartile range for those without asthma. Those with asthma also had a greater maximum value (approximately 5 liters) and median value (approximately 2.25 liters) as well. The results of this graph surprised me in a way similar to the emphysema graph as I expected patients with asthma to exhale less air due to problems of shortness with breath and more narrow airways.

# 

**Lines 142-182:**

These scatterplots observed relationships between Fever 1 Phase 2 and the categories of height (in inches), weight (in pounds), heart rate, body mass index, and age at the time of visit.

The only categories that showed a linear relationship (before adding the line of best fit) were height and age. For height, there was a positive linear relationship with Fever 1 Phase 2. Taller patients tended to be have a greater volume of air exhaled than shorter patients. For age, there was a negative linear relationship, where younger patients tended to have a greater volume of air exhaled than shorter patients.

The other categories did not show much of a relationship, if any at all. For weight, there was too much variation among those in the 100-200 pounds range to fully say there was a linear relationship. For heart rate and BMI, there was a lack of spread in the graph to see a linear relationship.

I tried to use the color dimension to observe if a patient's smoking status would provide for greater context in finding a relationship between the variables. However, this only helped with the age category, as most former smokers tended to have lower values of volume exhaled in a second.

# 

**Lines 185-215:**
The 95% confidence interval for gender does not include zero, which indicates there is not a significant difference in fever 1 phase 2 between males and females. 

(0.5574645,  0.6887909)
# 

**Lines 217-247:**
The 95% confidence interval for race does include zero, which indicates that there is a significant difference in fever 1 phase 2 between white and black patients.

(-0.0131721,  0.1267221)
# 

**Lines 249-279:**
The 95% confidence interval for smoking status does not include zero, which indicates that there is not a significant difference in fever 1 phase 2 between current and former smokers.

(0.07751252,  0.23520267)
# 

**Lines 281-311:**
The 95% confidence interval for emphysema status does not include zero, which indicates that there is not a significant difference in fever 1 phase 2 between emphysema patients and non-emphysema patients.

(0.8396444,  0.9670782)
# 

**Lines 313-343:**
The 95% confidence interval for asthma status does not include zero, which indicates that there is not a significant difference in fever 1 phase 2 between asthma patients and non-asthma patients.

(0.4336952,  0.5728375)
# 
**Lines 348-395:**

Confidence Interval for Slope of Height (inches): (0.08789432,  0.11238381)


Confidence Interval for Slope of Weight (lbs): (0.003059147,  0.005552061)


Confidence Interval for Slope of Heart Rate: (-0.013670538,  -0.005165759)


"Confidence Interval for Slope of BMI: (-0.010198350,  0.007756335)


Confidence Interval for Slope of Visit Age: (-0.03725624,  -0.02660256)


The height and age categories were the only categories of the five with a slope significantly different from zero.

Only positive values would be within height's 95% confidence interval. This reflects 95% confidence that the true population slope for height would be positive, suggesting a positive correlation between height and fever 1 phase 2. Meanwhile, only negative values were within age's 95% confidence interval, reflecting 95% confidence that the true population slope was negative and suggesting a negative correlation between age and fever 1 phase 2.

However, zero was within the confidence intervals for the other three categories, signifying 95% confidence that the population slope would not be significantly different from zero. This suggests lack of correlation between each of the categories with fever 1 phase 2.

This data reflects similar observations to the previous visual representation, as height and age were the only categories to show correlation on their respective scatterplots.
