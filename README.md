# O-rings-project
PESUIO Intro to ML Project - Challenger USA Space Shuttle O-Ring Data Set  
https://archive.ics.uci.edu/ml/datasets/Challenger+USA+Space+Shuttle+O-Ring

Team number: 2

Team members:
  Aaditya S Goel, Nitish Rathore, Taher Dossaji, Kumar Abhimanyu 
  
  # Dataset
  On the 28th of January 1986, 17% of the American population tuned in to watch the launch of the Challenger Space Shuttle. What was set to be a moment of great joy, however, turned into one of grief and sorrow. The space shuttle exploded even before it left the Earth's atmosphere. This catastrophe changed the way NASA functioned, forcing them to be more open to scrutiny and advice from the scientific community. But why did this disaster happen?
  An investigating committee called the 'Rogers Commission' led by Richard Feynman took up responsibility to find what caused this accident. They found that there are strong engineering reasons based on the composition of O-rings of the shuttle's booster propulsion system to support the judgment that failure probability may rise monotonically as temperature drops. One other variable, the pressure s at which safety testing for field join leaks was performed, was available, but its relevance to the failure process was unclear.
  No previous liftoff temperature was under 53 degrees F. Although tremendous extrapolation must be done from the given data to assess risk at 31 degrees F, it is obvious even to the layman "to foresee the unacceptably high risk created by launching at 31 degrees F".
  
  # Model
  The model that we are deploying is linear regression(both multi-variate and simple)
  Our independent variables are : Launch temperature in F, Leak pressure in psi
  
  Our dependent variable is 'The number of O-rings experiencing thermal distress'
  
  On plotting this model we get a positive intercept. The slope with respect to leak pressure is close to 0. This seems to imply that there isn't a strong correlation between the leak pressure of the risk to the O-rings. However, we notice that the slope with respect to launch temperature is negative. This seems to indicate that a decrease in launch temperature increases the probability of risk to the O-rings.
  
  # Testing
   Our rmse is 0.266 and our r_2 score is 0.354
   
   We have only 23 instances making it difficult to predict for sure how many O-rings were really at risk on that fateful day. Further analysis on this can be explored in the paper linked below in the summary.
  
  # Prediction
   The launch temperature on the 28th of January 1986, in Florida was 31 degrees Fahrenheit
    
   On predicting the number of O-rings at risk for the aforementioned temperature, our model expects around 2 O-rings to be at risk.
  
  # Summary
Although we can't predict exactly how many O-rings were at risk, what we can definitely infer is that the O-rings were at risk at 31 degrees Fahrenheit which led to the   tragedy. Extensive research has been conducted by various scientists over time to come with increasingly accurate models to predict values with small datasets. One such paper, specific to this dataset has been linked below. :) 
    
   https://www.ics.uci.edu/~smyth/courses/cs274/readings/draper95assessment.pdf
  # Contributions
   Code :-  All of us. duh!
   
   PPT :- Kumar, Taher
   
   readme :- Nitish, Aaditya
   
   Video :- All of us. duh!
