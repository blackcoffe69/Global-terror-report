# Introduction 

#### This is a Power Bi project on global terrorism, the reason for this project is to track the event of terrorism across the globle,to view the impact on human, properties, looking at the types of weapon been used, where attackers target more, period of the year where attacks are most likely to be high, the region of the world mostly affected by these attacks,the terrorist organisation involved, the casuality figures.
#### The goal is to get insightful knowledge on the trend and activites of terrorist organisations accross the globe.

# Skills demonstrated for this project:

#### * Data cleaning
#### * Filter/tooltips
#### * Critical analysis
#### * Data visualition
#### * Problem solving

# Problem statement

#### - To know the effect of global terror on human lives
#### - To study the kind of weapon used over time
#### - To check the trend of the facilities that gets attack most
#### - To view the part of the world that is most affected by this terror

# Data Sourcing 

##### After critically defining the problem with global terror and what we seek to achive with this analysis,I obtained a xlsx file from kaggle.com and imported it into my Power Bi. I cleaned the data, and then performed my analysis and created visualizations to help answer my questions.

# Data transformation/cleaning

#### The csv file was downloaded from kaggle.com imported into Power Bi,the data was dirty so I proceeded to use Power Query in Power Bi Bi to visualize,analyze the data theregy perfoming some critical cleaning using the filter/tooltips.The data set contains 58 columns that needs to be analyzed,cleaned before proceeding to visualization.

<img width="919" alt="glb blanks 1" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/e19bbbef-a01e-4425-8044-8f8ad1bcf3c3">

This column contains null values that will greatly affect the outcome of the data set,so I had to convert it to 0 since it is not blank,so if the data is available for it later it can be inputed.

<img width="928" alt="glb dirty" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/49b24292-3997-42ac-b73a-a34b50350224">

During the cleaning process,I noticed the summary contains dates of attacks with some blank cells,I need to extract the date out since it is critical to the task to evaluate the date of the attacks. 

<img width="910" alt="split" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/d3b66947-a35d-4ab8-9f0e-ccc709cc8bd8">

This was done by using the split function by delimeter.The blank cells were removed using the filter tool by unchecking the box that creates an effect that applies to all the cells containing blank cells.

<img width="904" alt="glb date of attacks" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/3daf7e7a-3cc2-4014-acdc-b232ac9acb6a">

This is the result after spliting the date from the details about the attack,the column had to be named Date for easy identification.

<img width="928" alt="glb blanks" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/918bf367-b3c2-4385-bfdd-f7ea5da57762">

The provstate column also contain some blank column that was removed with the filter tools


# Data Modelling

#### No data modelling is required for this project.


# Analysis and Visualisation :


#### I choose to create simple and easy-to-understand visuals. To reflect the situation of global terror, I used their colors of red, white. These colors are also bold and eye-catching, which helps to make the visuals more memorable. I wanted to ensure that the visualization would be easily understood by anyone who viewed it, regardless of their level of expertise.


<img width="586" alt="count" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/7d1b001d-203a-4fbf-a4c4-d4cecd57f56f">

#### I created a silcer that contains all countries so that this will help when choosing each countries anyone can easily see the trends for every tables I created in project. Below it I gave a brief history of the global terror with the view of the year period from 1970 to 2015 which is what we are looking at in the data set provided. The total count of the country involved is 57 country,provided this using the card visualisation tool. Total sum of attacks using card method also is 2210,Total number of people killed 468,total number of wounded people was 330 while nationalities targted was 11k.


<img width="724" alt="Sum of attack type" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/43b93047-dc65-45d3-8a7e-efe2c25b56cd">

1. Attack type 1, Sum of attack type by Bombing/Explosion was 129 and sum in a day was 709
2. Attack type 1,Sum of attack type by Armed assault was 24 and sum in a day was 158
3. Attack type 1,Sum of attack type by Unknown was 9 nd sum in a day was 14
4. Attack type 1, Sum of attack type by Assasination was 1 anad sum in a day was 14




