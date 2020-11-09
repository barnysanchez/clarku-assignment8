# Instructions for Assignment 8 submission 

***THIS IS PART 2 OF YOUR CAPSTONE PROJECT***

(The purpose of this assignment is for you to delivered a trained model that addresses your project proposal. This model needs to be trained with the data set that you harvested from the previous assignment 7.)

- Please copy the contents of this markdown as the starting template of your assingment. 
- The resulting file from this programming assingment must be submitted to the private repo you submitted for my review during assignment one. 
- The name of the file has to follow  naming convention:  *lastname*_week11.ipynb
- There are four sections of this assignments required to receive full credit. 
- Please see that the expected file is a Jupyter notebook which contains Python code and markdown, just like shown in class and in my recap video from week 2. 


# Section 1) Summary of your project (10%)

Summarize in 2-3 paragraphs the project that you sought out to resolve. 

Paragraph 1 - Synthesis of your project. 

Paragraph 2 - What kind of ML architecture did you chose to use. Short described what you did about your data set.

Paragraph 3 - What is your own defined success criteria. 

```
Example:

1) As a consumer of food, I wanted to find out how many calories I needed to eat in November, so that in December I can still fit in my clothes. This was a regression problem. 

2) I chose a supervised ML model using my own data set from the app on my phone that tracks my daily food ingestion. I collected it for 2 months, tabulated, and did some feature engineering to combined healthiest and more filling types of foods. 

3) When I weight myself every 2 days, I should be within 5% of my baseline weight. My starting weight at the start of the experiment was 200 lbs. 
```

# Section 2) Show the code and architecutre of your ML (20%)

This is a descriptive section. Explain the architecutre of your ML model. This includes the different layers in use, and what specific accuracy/error/loss you are using to test your model. 
If you want to explain every cell of your Jupyter notebook in this section is fine if this is simpler for you to process.

# Section 3) Show the output of your model training with your harvested data set (30%)

Show how you loaded your data set. 

Show or explain how you split your data set in training and test data sets.

Show your model training and accuracy/error/loss.

Visualize the performance of your model (accuracy/error/loss). You can use for this calculations, graphs, tables. 

# Section 4) Save your ML model for distribution (10%)

Show how you saved your ML model. In addition to showing the code, the expectation is that in your repo your ML model is present. 

In your private repo, ensure that you save your trained ML with following the convention: ***lastname***_week11_model.(extension)


# Section 5) Inference test of your model (20%)

Explain the scope of your machine learning model. In other words, under which circumstances or what creteria has to be met in order for your model to be successful?  For example: My model recognizes if people are happy or crying. Given the data set that was used, the model is only good if the person crying has tears on his/her face. Without tears some people may seem to be laughing (have you seen the Joker from Batman?)

Explain in one cell how you are testing the inference. For example:  To test inference, I took a picture of my brother, imported it to my system, and ran my ML model to see if he was serious and laughing. Given my own definition of success criteria, I should have 80% or greater chances of asserting that my brother is serious or laughing. 

Show the testing of your inference. 

# Section 6) Summary (10%)

Given your own definition of success of this project. Were you successful?  

- If yes:  thinking back, what was the hardest part?  what would you have done different? 

- If not: what went wrong?  can this project be saved? what would you need to make it successful?


