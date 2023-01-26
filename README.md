# data-visualization-challenge

# This code analyzed drug regimen data for 9 different drug regimens and a placebo group aimed at reducing tumor volume of squamous cell carcinoma in mice. This study evaluated tumor volume of the mice on the different regimens at various time points over the course of the study. One mouse had some duplicated data that did not match, so that mouse was not included in the analysis.

# Looking at the initial summary of the statistical data for each regimen, based on the tumor volume, it is clear that the Capomulin regimen and the Ramicane regimen both had comparable results that were noticeably better than the other drug regimens. Both of those regimens had smaller mean tumor volumes, smaller median tumor volumes, and smaller variance, standard deviation, and standard error of the volumes. All other regimens had much higher numbers in all categories. See table  of summary statistics below.
![image](https://user-images.githubusercontent.com/118322354/214771548-1ad6fecd-730a-415c-a789-8968074b67a0.png)

# Most of the drug regimens had similar total numbers of timepoints tested, with the exceptions of Ramicane and Capomulin having more and Propriva having fewer timepoints tested. See the following chart.
![image](https://user-images.githubusercontent.com/118322354/214772187-6197988b-f9be-405d-9681-b2a708f41641.png)

# The sexes of the mice in the study were fairly equally distributed with a few more male mice in the study. See the following figure.
![image](https://user-images.githubusercontent.com/118322354/214772402-743bfe8c-4044-4d34-aea0-b3608f716ebd.png)

# The data points for Capomulin, Ramicane, Infubinol, and Ceftamin mostly fell within expected ranges based on the quartiles of the final tumor volume for each mouse, with the exception of one much smaller tumor for one mouse on the Infubinol regimen. Further study may be needed to determine what other factors may have been present for that mouse. See following figure.
![image](https://user-images.githubusercontent.com/118322354/214773295-08c6c1aa-167b-457b-8079-45de2802e15a.png)

# One mouse on the Capomulin regimen was isolated and its tumor volume over time was plotted as an example of how the drug can work. See the following figure.
![image](https://user-images.githubusercontent.com/118322354/214773550-08a61ad3-8354-48ee-9d96-f0707fa27920.png)

# The mice on the Capomulin regimen were isolated and the average tumor volume for each mouse was calculated and plotted against the weight in grams of that mouse. A regression was then calculated as well as a pearson correlation coefficient. There is a strong correlation between the weight of the mouse and the average tumor volume for that mouse with a pearson correlation coefficient of 0.84. See the following scatter plot.
![image](https://user-images.githubusercontent.com/118322354/214774049-efeb4656-8af4-49cf-aed0-887b609d99c5.png)
