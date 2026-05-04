# Cosmic-Evolution-26
Used in Cosmic Evolution class Spring 2026.

My project is focused on determining galaxy morphology and star formation activity using SDSS data. I use galaxy magnitudes in different filters, and concentrations based on radii in order to carry out this data analysis. 

The file titled 98TDataAnalysis.ipynb is the main analysis Jupyter notebook

The Data Source for my project is SDSS DR17 which was accessed using a SQL query through astroquery. This step is shown within my Jupyter notebook. 

In order to run my notebook, astroquery, matplotlib, and  numpy are libraries that are needed to run the code. 

The concentration index number divider that gives spiral_approx and elliptical_approx is a rough estimate that was gathered following Strateva et al. (2001). https://iopscience.iop.org/article/10.1086/323301/pdf 
