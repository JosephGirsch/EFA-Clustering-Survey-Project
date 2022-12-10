# Welcome to the Survey Clustering Analysis Project!

As government contractors, the United States Air Force (USAF) provided our team with survey data in order to to identify overall trends in organizational climate. 
Survey questions were asked on a variety of topics including: training, resources, morale, and leadership. The USAF leadership wanted to see if we could pair the survey
responses with group morale data in order to identify trends in why some units had moderate to positive group morale and others had plummetting morale scores. 

As part of this project, I combined an Exploratory Factor Analysis and a applied Gaussian Mixture cluster model to group the service members into clusters based on their responses. 
The EFA processing step was required due to the correlated nature of similarly worded survey questions. Out of the survey responses and paired demographic 
variables a story could be told that explained the deviations from median group morale. Some units belonged to a cluster that had great confidence in their 
leadership and displayed overwhelming group morale. Other units could be identified as having below average group morale due to concerns with 
training or scheduling. The most significant finding were units that belonged to a small cluster associated with extremely negative group morale and 
extremely high bullying and harrassment scores. The USAF Leadership was extremely pleased for us to identify these units for them. 

The names of USAF units, service member unit identification, and descriptions of source data were changed or removed to preserve privacy.
But the tools and methods as well as some of the sanitized results are still available for display. 

* Input/survey_data_processed_scrambled.csv: The (sanitized) source of data for the survey analysis. Contains the individual service member responses to survey questions along with proxies for their associated Wings and Locations (all sanitized to preserve privacy)
* Simplified_Clustering_scrambled.ipynb: The (sanitized) jupyter notebook which loads the survey data, conducted the Exploratory Factor Analysis (EFA), and produced the results of the Gaussian Mixture cluster model.
* Sanitized Cluster Analysis Presentation.pptx: A (sanitized) subset recreation of the PowerPoint results I presented to USAF leadership in 2022. 


The jupyter notebook was run on an Anaconda environment with the following packages installed:
* pandas
* numpy
* matplotlib
* factor_analyzer
* sklearn

No compatability issues were encountered using the most up to date versions as of 12/10/2022.
