Descriptive statistics:
 
For each variable (DBH, Height):
    Compute descriptive statistics:
	Return a summary table with statistics for each site


Data Visualization:

For each variable (DBH, Height):
    Create a boxplot:
        X-axis: 'Site'
        Y-axis: Variable (DBH or Height)
        Apply defined color palette for DBH
		Apply Set2 color palette for height
        Display the plot

		
Statistical Analysis:

Perform Levene’s test for DBH:
    Group data by 'Site'
    Compute variance for each group
    If p-value > 0.05:
        Variances are equal (assumption met)
    Else:
        Variances are significantly different
		
		
Fit an ANOVA model for DBH:
    Define the model: DBH ~ Site
    Fit the model
    Compute ANOVA table
    Report F-statistic and p-value

If p-value < 0.05:
    Conclude that at least one site has a significantly different mean DBH
	

Perform Tukey’s HSD for DBH:
    Compare all pairs of sites
    Report mean differences and significance levels
	
The same statistical tests (Levene’s Test, ANOVA, and Tukey’s HSD) are repeated for Height to examine differences in tree height across sites.

