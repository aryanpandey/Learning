# ANOVA Partitioning and Test

### One-Way ANOVA
A particular factor in this test has more than 2 groups or levels of interest. For example, if the Subject of study is our factor for affecting the mean annual salary of a graduate then possible levels of interest could be Mathematics, Economics, Environmental Sciences or Political Sciences.

Basic Idea behind a one-way ANOVA is to take independent random samples from each group, then compute the sample means for each group. After this we compare the variation of sample means among the groups to the variation within the groups. 

### Calculating the Sum of Squares
The total amount of variability in a One-Way ANOVA comes from two possible sources:
- Difference among the groups, called Treatment(TR)
- Difference within the groups, called Error(E)

Total SS = Treatment SS + Error SS, SS being the Sum of Squares

The degrees of freedom is also calculated in the same way. Total DOF = Treatment DOF + Error DOF

### Assumptions for the One-Way ANOVA test
- All observations are randomly sampled and are independent of each other
- Values in each sampled groups are assumed to be sampled from a Normal Distribution.
- Ideally, the ariance of all the groups are equal. As a Rule of Thumb if the ratio of the largest to the smallest is less than 2, we say that the criteria is fulfilled.

#### Post this we calculate the F statistic to test our hypothesis of "All Means are equal"

Link for the Notebook containing Supporting Code: [Notebook](../Notebooks/ANOVA.ipynb)
