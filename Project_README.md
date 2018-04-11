# Project_Weber

#For my Master's thesis, I am studying the stress response and post-release mortality in blacktip sharks that are caught by 
recreational fishermen in 2 different fishing modes (shore-based vs. charter-based). I have sampled 32 blacktip sharks so 
far (including both shore-based and charter-based), and for each of those sharks I recorded numerous biological and environmental variables, which are outlined below. The stress parameters (pH and lactate) were analyzed from a blood sample. The outcome of the shark (i.e. whether it died or survived post-release) was assessed through satellite and acoustic tags.

#The variables that you will see in the analysis include:
Water Temp (the temperature of the water at the site the shark was caught)
Fork Length (the length of the shark)
Fight Time (the time the shark was on the line)
Handling Time (the amount of time the shark was handled for)
pH (indicator of stress, and in particular, acidemia)
Lactate (indicator of stress, and in particular, the degree of the metabolic acidosis)
Hook Location (the location of the hook, e.g. in corner mouth, bottom mouth, stomach, etc.)
Condition (a number from 1-5 assigned based on the sharks behavior at release)
Mortality (binary variable, where "1" indicates a mortality and "0" indicates a survivor)
Fishing Method (shore vs. charter)

#The objective of this project is to conduct a binomial logistic regression, to determine if we can predict for the outcome 
of a released shark (i.e. whether the shark survives or dies) using the variables measured (and described above). 

#The "Binomial Logistic Regression" markdown file will walk you through the analysis step-by-step, with written code (denoted with a #) throughout. Because of the large number of variables measured (all of which could influence, and thus be used to predict, post-release mortality), I begin with a PCA - to shed some light on the variables explaining the majority of the variation in the dataset. After eliminating 2 variables (as suggested by the PCA), I take a backwards stepwise approach to the binomial logistic regression - beginning with the full model (i.e. including all potential variables) and then removing the least significant variable at each step. 
