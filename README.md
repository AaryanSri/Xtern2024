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
