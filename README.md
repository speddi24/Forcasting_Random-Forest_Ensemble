# Forcasting_Random-Forest_Ensemble
Forcasting Future temperature using Random Forest

Roadmap:

Below is a brief guide of steps followed while programming. The following steps form the basis for any machine learning workflow once we have a problem and model in mind:

 1. State the question and determine required data
 2. Acquire the data in an accessible format
 3. Identify and correct missing data points/anomalies as required
 4. Prepare the data for the machine learning model
 5. Establish a baseline model that you aim to exceed
 6. Train the model on the training data
 7. Make predictions on the test data
 8. Compare predictions to the known test set targets and calculate performance metrics
 9. If performance is not satisfactory, adjust the model, acquire more data, or try a different modeling technique
10. Interpret model and report results visually and numerically
    
Following are explanations of the columns:

year: 2016 for all data points   
month: number for month of the year    
day: number for day of the year
week: day of the week as a character string   
temp_2: max temperature 2 days prior   
temp_1: max temperature 1 day prior    
average: historical average max temperature    
actual: max temperature measurement     
friend: your friend’s prediction, a random number between 20 below the average and 20 above the average
