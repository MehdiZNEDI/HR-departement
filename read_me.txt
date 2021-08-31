Task #1 @Human Resources Department: Develop an AI model to Reduce hiring and training costs of employees by predicting which employees might leave the company


Hello, everyone, and welcome to this new case study in this case study.


So if you have the wrong people, that will cost you a ton of money, would cost you time, and that

can actually might lead maybe obviously at some point to bankruptcy, for example, of sort of some

of these corporations.


Hiring and retaining top talent is an extremely challenging task that requires capital time and skills.

Small business owners spend 40 percent of their working hours on tasks that do not generate any income,

such as hiring, for example, and companies spend 15 percent to 20 percent of the employee's salary

to recruit a new candidate, which is a massive amount, especially for large corporations with thousands

of employees.


By developing accurate prediction models that could predict employee retention, you could potentially

save the company hundreds of thousands of dollars.


*First:

understand how to leverage the power of data science to reduce employees turnover and transform

human resources department.

*Second:

-understand the theory behind logistic regression and random forest classifiers.

-Train in logistic regression classifier and random forest classified models using cycle learn.

-Apply sigmoid functions to obtain probability load and manipulate data set using pendas data frame.

-Develop a function in Python and apply it to append this data frame.

-Perform exploratory data analysis using matplotlib and seabourne libraries, plot kernel density, estimate

plotts or Kathee for short box plots and count plots.

-Convert categorical variables into dummy variables.

-Divide datasets into training and testing data using Saikat.

-Learn understand the theory and intuition behind artificial neural networks and how to apply them to

-perform classification tests, evaluate classification models and present results using confusion,

matrix and classification reports, and understand the difference between precision recall and EF1 score.

And that's what I have.




==================================================================================================================================

Hello, everyone we are going to predict which employees in a company are more willing to leave or are tending to basically leave the corporation.

*question to ask :

-why do employees leave?

-Why do they want to stay?

-How can we make them motivated?

-what is the cost associated with basically employees leaving the company?

**so in this project:

-1-learn or understand the problem statement and business case.

-2-import our libraries and data set 

-3-visualize our data set.

-4-create our training and testing data set and perform data cleaning

-5-learn and understand the intuition behind three different classifiers that we are going to use in this case study.

-6-learn how to assess these classifiers.

-7-learn about confusion, matrices and so on.

-8-train and evaluate our different classifiers.







==> it's really hard to tell which employees are planning to stay so we can compensate them, for example,

or maybe which employees are tending to leave, for instance.

So if we have some employees and they are top talent, they actually deliver a massive amount of value.

You actually need to compensate them properly.

-You need to retain them.

-You need to train them.

-You need to give them bonuses, for example, for them to stay.


So hiring and retaining employees are extremely complex tasks and they actually require a lot of time

skills and capital investments and small business owners.

These are kind of quick facts that I found that actually really interesting from the source here.

So small business owners spend 40 percent of their working hours on tasks that do not generate any income,

such as hiring.

Can you imagine, you know, the amount of brainpower that business owners consume or like, you know,

like I kind of put towards hiring the right people and they are not using that to generate any other

income, for example.

Another point is companies spend around between 15 percent to 20 percent of the employee's salary to

recruit a new candidate.



An average company loses in anywhere between one percent and 2.5 percent of their total revenue on the

time it takes to bring in a new hire up to speed.

So the problem doesn't stop by actually hiring the right people.

The problem is in actually training them because, you know, even if you have a skilled employee for

them to actually like, you know, like understand the systems, understand the processes, you get

like up to speed with their team and so on, there is a lot of revenue lost in that time.

If you have a corporation between zero and five hundred employees, which is again a lot of money per

employee, and it takes 52 days on average to fill a position, just imagine again, that's a lot of

time.

==========================================================================================
Steps :


1-Declaring packages
2-Collecting Data
3-Exploring and Cleaning Data 
4-visulize all data histogram
5-create the corollation table to see those who are strongly corrolated
6-plot the strongly corrolated features
7-transform non numeric data into numerics using :
       from sklearn.preprocessing import OneHotEncoder
       onehotencoder = OneHotEncoder()
       X_cat = onehotencoder.fit_transform(X_cat).toarray()

8-make sure to have all numerci data in the data frame
9-split the data into train-test-validation
10-train the model using x_train,y_train
11-calculate the accuracy using y_test,x_test 
12-Testing Set Performance using confusion matrix
12-print the classification report
13-optimize for exemple by increasing the number of sampels


