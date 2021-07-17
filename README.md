# HabermannsCancerSurvivalDataset_EDA
EDA on Haberman’s Cancer Survival Dataset
Understanding the dataset
Title: Haberman’s Survival Data
Description: The dataset contains cases from a study that was conducted between 1958 and 1970 at the University of Chicago’s Billings Hospital on the survival of patients who had undergone surgery for breast cancer.
Attribute Information:
Age of patient at the time of operation (numerical)
Patient’s year of operation (year — 1900, numerical)
Number of positive axillary nodes detected (numerical)
Survival status (class attribute) :
1 = the patient survived 5 years or longer
2 = the patient died within 5 years

Conclusion for the Habermanns Cancer Survival Data:

1.The Given dataset is Imbalanced Dataset as it does not have the equal number of datapoints for each class.

2.In the UniVariate Analysis like 1D-Scatter plot, Histogram,PDF & CDF, Box Plots and Violin Plots, we can observe that No of Auxillary Nodes is playing a role,which is giving little assumptions.So,The Number of Auxillary Nodes is the well important Feature of given Data set.

3.In the Bivariate Analysis like 2D-scatter plot and Pair Plot,the given dataset is not linearly separable.There is so much of overlapping.The two classes are not well separated in any one of the Bivariate Plots.

4.Well,The Box plots and Violin plots are giving the better info comapared to the PDF and CDF in the form of Percentiles.

5.But the Assumptions what we observed are not well enough to Build a model of classifying the survival status,as the classes are always overlapping.
