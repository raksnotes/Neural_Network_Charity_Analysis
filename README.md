# Neural_Network_Charity_Analysis


## Purpose: 
The purpose of this analysis is to preprocess data and build a neural network for allocation of investments in several charity organizations. 

Results: Using bulleted lists and images to support your answers, address the following questions.

## Data Preprocessing
### What variable(s) are considered the target(s) for your model? (shown below)
### What variable(s) are considered to be the features for your model? (shown below) 
![image](https://user-images.githubusercontent.com/116187123/230995721-f180f90e-4a19-48d2-8407-19aeb810bac1.png)

### What variable(s) are neither targets nor features, and should be removed from the input data?
The dummy variables can be dropped from the input data. 
![image](https://user-images.githubusercontent.com/116187123/230996073-7462b4de-a4f6-4b11-8085-cd8b53707d2b.png)

## Compiling, Training, and Evaluating the Model
### How many neurons, layers, and activation functions did you select for your neural network model, and why? 
Three 
## Were you able to achieve the target model performance? 
No, it was just 2% below the target model performance. 

## What steps did you take to try and increase model performance?
When optimizing the model, I dropped the INCOME_AMT & USE_CASE Columns shown below: 
![image](https://user-images.githubusercontent.com/116187123/230989346-87297123-785a-4190-a497-ba4fc05f3a21.png)

Each attempt that I ran the optimized model: 
I used the epoch from Deliverable 1 & 2, increased the epoch to 55 for attempt 2, increased epoch to 105 for attempt 3 (images shown below) 
I've also changed the nodes_layer values to see if that would increase the accuracy score as well. (images shown below) 

![image](https://user-images.githubusercontent.com/116187123/230989906-751011b2-7d38-4d88-a713-429a1f53795e.png)

![image](https://user-images.githubusercontent.com/116187123/230990077-7a4838d5-36d9-44cc-bfce-3ea81b5f5ac6.png)


![image](https://user-images.githubusercontent.com/116187123/230990166-997866a7-685c-4c92-be5b-5ca7d503f555.png)

![image](https://user-images.githubusercontent.com/116187123/230990219-7cc2b0ec-9fbb-4226-b56c-5ce858bbcce1.png)


![image](https://user-images.githubusercontent.com/116187123/230990333-aab1a863-cd5f-45fe-845e-576f00529574.png)

![image](https://user-images.githubusercontent.com/116187123/230990396-02c32303-bec3-416f-8278-18d03bd759b0.png)

Summary: Summarize the overall results of the deep learning model. Include a recommendation for how a different model could solve this classification problem, and explain your recommendation.


Overall, once I had optimized the model, the accuracy score was 73.9% which came really close to the target performance. I recommend a model with lesser columns and 
a larger epoch value because when I optimized the model with these characteristics, it was able to be brought up to a higher accuracy score, which is wh. at would be 
ideal for this analysis.

References: (shown in commentary of ipynb files)
https://stackoverflow.com/questions/73509378/getting-keyerror-not-found-in-axis-when-trying-to-drop-a-column-from-datafram
