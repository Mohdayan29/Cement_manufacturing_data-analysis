# Cement_manufacturing_data-analysis

Summary of Findings
My main areas of interest in this dataset are the factors that affect or are directly related to the compressive strength values determined from the concrete mixture samples. The findings I derived are based on a cleaned dataset with no null or zero values in any column.

During the exploration, I found the following:

The majority of the concrete samples fall in the moderate strength category, followed by the high category. The fewest observations are in the 'low' category, while the 'very high' category has the least number of observations.
Across each specific range of cement quantity used, minimal strength increases with increasing quantities of cement.
The lower the water-to-cement ratio, the greater the compressive strength.
Grade A (the lowest water-cement ratio) has the highest occurrence, while Grade F has the lowest. Grade C has the second highest occurrence, followed by Grades B, D, and E in that order.
Maximum compressive strength increases with a decreasing water-to-cement (w/c) ratio.
The median value of the fine-to-coarse aggregate ratio decreases from Grade A to C (water-cement ratio), then increases from Grade D to F.
Low-quality water-cement Grades D, E, and F have maximum compressive strength values of about 40 MPa, whereas higher Grades A, B, and C have compressive strength values exceeding 40 MPa.
Only Grade A (water-cement ratio) has cement quantities of 300 kg and above, while the rest have cement quantities less than 250 kg.
Grade A contains concrete samples with superplasticizer quantities around 15 kg, while the other grades contain superplasticizer quantities less than 15 kg.
Slag is used to complement cement during concrete mixing, and within each water-to-cement ratio category, an increased quantity of slag improves the maximum compressive strength.
The mode of the aggregate ratio, which occurred between 0.73 to 0.9, is probably too small to significantly affect the compressive strengths of the concrete samples in this dataset.
For presentation, I will introduce the 1st, 4th, 5th, and 10th findings as key insights. Other findings focus on different variables in the dataset or are somewhat repetitive of the chosen four key insights.

Key Insights for Presentation

I introduced the distribution of compressive strength across the samples and also showed the categorical percentage proportion of compressive strength in the dataset. I then showed the distribution of the water-to-cement ratio, followed by the bivariate relationship between compressive strength and water-to-cement ratio. Finally, I communicated the significance of slag in concrete mixtures through multivariate plots depicting the relationships between slag, cement, compressive strength, and water-to-cement ratio. Design improvements include increasing the data-ink ratio by removing borderlines, adding proportion labels to bars for easier comprehension, using appropriate titles and axis labels, and removing ticks where necessary. I also used different color palettes for different qualitative variables to avoid ambiguity.
