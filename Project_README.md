# Project_Weber

#For my Master's thesis, I am studying the stress response and post-release mortality in blacktip sharks that are caught by 
recreational fishermen in 2 different fishing modes (shore-based vs. charter-based). I have sampled 32 blacktip sharks so 
far (including both shore-based and charter-based), and for each of those sharks I recorded the 'Fight Time' (i.e. time on 
the line), 'Handling Time' (i.e. time handled), and 'Fork Length' (i.e. length of the shark). I also drew blood from sharks 
to assess stress parameters ('pH' and 'Lactate' are included here). Upon the release of each shark, a 'Condition' (ranging 
from 1-5; 1 being showing no signs of stress and 5 being moribund) was assigned, based on the sharks behavior upon release. 
The 'Water Temperature' at each site was recorded. Finally, each shark was tagged, in order to monitor survivorship 
post-release. 

#The objective of this project is to conduct a binomial logistic regression, to determine if we can predict for the outcome 
of a released shark (i.e. whether the shark survives or dies) using the variables measured (and described above). 

#The "Binomial Logistic Regression" markdown file will walk you through the analysis step-by-step, with written code (denoted with a #) throughout. Because of the large number of variables measured (all of which could influence, and thus be used to predict, post-release mortality), I begin with a PCA - to shed some light on the variables explaining the majority of the variation in the dataset. 
