# Neural_Network_Charity_Analysis

## Overview : 

The company, Alphabet Soup, wants to be able to predict where to make investments. Utilizing machine learning and neural networks to apply features on a provided dataset a binary classifier is created that is capable of predicting whether applicants will be successful if funded by Alphabet Soup. The initial file has 34,000 organizations and a number of columns that capture metadata about each organization from past successful fundings.

## Results : 

Using bulleted lists and images to support your answers, address the following questions.

**Data Preprocessing**

- What variable(s) are considered the target(s) for your model?

![image](https://user-images.githubusercontent.com/101137700/183266540-52f2d2aa-2b86-417d-91fd-972936c8f85e.png)

- What variable(s) are considered to be the features for your model?

![image](https://user-images.githubusercontent.com/101137700/183266564-84d01060-6c75-490d-bd3c-989cdecb7851.png)


- What variable(s) are neither targets nor features, and should be removed from the input data?

![image](https://user-images.githubusercontent.com/101137700/183266578-fdeb9436-24c1-432c-979f-4b4b5396a456.png)


**Compiling, Training, and Evaluating the Model**

- How many neurons, layers, and activation functions did you select for your neural network model, and why?

The orginal mode architecture and result :

![image](https://user-images.githubusercontent.com/101137700/183266975-29881741-4ea1-46e3-9af1-79cc15b20ff3.png)

![image](https://user-images.githubusercontent.com/101137700/183266987-553fc7cb-02f0-455a-8457-57cdda6259a1.png)

![image](https://user-images.githubusercontent.com/101137700/183266996-df79160e-2851-4396-bc05-7c29bad6e1f8.png)

- Were you able to achieve the target model performance?

Yes

![image](https://user-images.githubusercontent.com/101137700/183267036-97878871-9e4d-4221-ae57-e8c4c1e9c5b7.png)

- What steps did you take to try and increase model performance?

Increasing the parameter amount by keeping the NAME column and increasing the model depth :

![image](https://user-images.githubusercontent.com/101137700/183267048-0c40baeb-7a7d-4862-b560-72ec95ce6d12.png)

![image](https://user-images.githubusercontent.com/101137700/183267054-a979f41a-25cf-4702-b0fa-771a363e8754.png)


## Summary: 

The results are promising and with a better cpu to run more epochs I believe the model performance would be much higher. 
