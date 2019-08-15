# Language-Psychiatric-
Can Language and Grammar tests detect the prescence of Psychatric disorders?
 
 I work on a public data set reported in Hartshorne, Tenenbaum, & Pinker. A Critical Period for Second Language Acquisition: Evidence from 2/3 Million English Speakers. This Dataset contains the results of an English language exam given to 600,000 people. The Data has many features from the participants, for example years spent in English speaking country, native language, age, correct answers, presence of psychiatric disorders and many more. While performing EDA on the data set, I found that  individuals in the US which presented psychiatric disorders were very likely to have median to excellent results (staying above the lower threshold of those which did not present psychiatric disorders), this is shown in plot1. Further exploring the data, this observation appears as if it is not by random chance. The individuals with psychiatric disorders seem to be evenly distributed among the categories of education and years living on English speaking countries (as shown in plot 2). 
 
  In  GrammarPsych  several types of classifiers are trained to predict the likelihood that an individual presents psychiatric disorders based on it's answers to the grammar Quiz. On a separate note, I also train classifiers to predict whether the participant is a speaker of Ebonics. 
  
   In GrammarPsychNeural, as above, a simple neural network is trained to predict whether the participant presents a psychiatric disorder.
   
   I have provided the ROC curves for the testing data for each for the models within the Psychiatric predictor and the Ebonics predictor.
   
