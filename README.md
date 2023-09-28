# ML1_H23
Fred Christiansen 

What the project does:
	
The task at hand is to estimate how long patients will be in the hospital using various features from a patients medical history. 

This is done by training a model using machine learning by following the 7 steps for machine learning.
1. Frame the problem and look at the big picture
2. Get the data
3. Explore the data to gain insights
4. Prepare the data to better expose the underlying data patterns to machine learning algorithms
5. Explore many different models and short-list the best ones
6. Fine-tune your models and combine them into a great solution
7. Present your solution

This solution has 2 models:
1. A model which predicts based on all the 25 features, this is the most accurate one.
2. A model which predicts based on 6 selected features, this is less accurate but much easier to run in the gradio web app.

Finally it contains a Web application based on gradio which performs an estimated lenght of stay based on 6 features 
which are submited by the user. 
