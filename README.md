# Xtern2024

Using an initial data analysis, we see a couple of patterns. First is the year spread - only years 2 and 3 seem to be present in this data. So, we are training our model to predict only that target audience.

<img width="576" alt="Screenshot 2023-10-17 at 3 17 44 AM" src="https://github.com/AaryanSri/Xtern2024/assets/77908013/298aa705-b3f7-4754-8107-b929c77cc375">

There is also a large bias in the data towards certain universities. Here are the results for Year 2 students, followed by Year 3 students.
<img width="566" alt="Screenshot 2023-10-17 at 3 32 33 AM" src="https://github.com/AaryanSri/Xtern2024/assets/77908013/d51da930-b146-45d6-85dd-3a07b40a4bb3">

<img width="569" alt="Screenshot 2023-10-17 at 3 32 52 AM" src="https://github.com/AaryanSri/Xtern2024/assets/77908013/a53d0333-d8da-4a50-94e6-83aad3ee1c82">

The universities Butler University and Ball State University and ISU have more influence on this model's training, so other colleges like Purdue University and Evansville may not have accurate predictions. These biases in the data will affect the results of our model to be tailored towards a hyperspecific audience.

# Ethical Implications 

This will result in inaccurate findings when deciding what their order is for other schools that do not have as much data. This can lead to inaccurate predictions which is not beneficial to the staff that this AI is trying to benefit.

# Business Implications

It is probably best to deploy this model to the universities with the most data. This will result in more accurate predictions, more profit due to less 10% coupons, and a happier staff as they do not need to guess the order. So BU, BSU, AND ISU will benefit the most from this ML model.

# Technical Implications

Our model needs more data about more universities and more students if it will get more accurate in its predictions and findings. More specifically, it needs to be finetuned on under-utilized university data to get better overall results and feedback.

# Model Selection, Training, and Testing

I decided to go with a Classification Tree Model since we are dealing with categorizing known products based on unknown data that we are training our model off of. This can lead to good predictions without a very complicated structure like a CNN. Then, I transformed all non-numerical data like year and college into numerical data to better train the model. The rest required just adding the trained model and the results into the tree, and then judging the accuracy by comparing the predictions with the tested results from the dataset.

# The Results

The model surprisingly well. I got an overall accuracy of 67%, with the most accurate results being Indiana Pork Chili, Ultimated Grilled Cheese Sandwich, and Indiana Corn on the Cob. 

# Considerations

To be honest, this is an accurate model that may be more efficient than human guessing. However, to better capitalize on its performance, we would need what any machine learning model needs: more data. My data breakdown in the beginning shows the biases and problems of the data and fixing these errors can guarantee better performance and save costs to the business.
