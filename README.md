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

### Sum of Attack type:

<img width="724" alt="Sum of attack type" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/43b93047-dc65-45d3-8a7e-efe2c25b56cd">

1. Attack type 1, Sum of attack type by Bombing/Explosion was 129 and sum in a day was 709
2. Attack type 1,Sum of attack type by Armed assault was 24 and sum in a day was 158
3. Attack type 1,Sum of attack type by Unknown was 9 nd sum in a day was 14
4. Attack type 1, Sum of attack type by Assasination was 1 anad sum in a day was 14

### Sum of People Wounded in a Day :

<img width="670" alt="sum of nwounded in a day" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/75ff9897-22b5-47c2-ae67-99e3c8abc8f1">

. Within the space of 30 days in a month 24th has the highest number of people wounded 
. The 4th of the month comes up with no one wounded with value of 0

### Target type by Sum nationalities :

<img width="662" alt="Tagret type and sum of nationality" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/5a43ffb8-a31d-4c2f-8f64-af4b7f8f0203">

The treemap shows the target type with the nationalities involes:

1. Vechile has the total of 1270 nationalities that were attacked in a vehicle
2. Soldier has the lowest of 4nationalities attacked 

### Total by month and year :

<img width="628" alt="Suicide by year" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/4f4be622-b727-4ad3-918e-04b23d7c91e0">

1. The year 2005 ranks the highest with the total number 310 suicide within the space of a month.
2. The year 1998 has the lowest with the total number of 32 within a month

#### The next slide has the card for for total sum of property damaged 201 while 2210 is total number of people wounded.

## Attackers nationality and Targets

<img width="657" alt="attackers nationality" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/947087d6-d300-456c-8cd2-8aa3f15d5f86">

. From this table the highest nationality that were attacked were in vehicles with the total sum of 1270
. Soldiers were the least with a total number of 4

## Weapon type by year

<img width="665" alt="Weapon type by year" src="https://github.com/blackcoffe69/Global-terror-visualization/assets/154302970/2c122f64-cee8-4b4f-aecb-37cb0508c45d">

This shows the number of weapon used for attacks with each year and total number of people affected,year 199 ranks the highest with total number of weapon used 6,people affected to be 238
