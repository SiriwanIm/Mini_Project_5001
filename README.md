<center>
<div class="alert alert-success">
<h1>Mini Project 5001</h1>
<h3>Global mental health and happiness analysis </h3>
</div>
</center>

<div class="alert alert-info">
<h3>Current Situations:</h3>
</div>

Mental health is an essential part of people’s lives and society. Poor mental illness affects well-being and quality of life. Mental health problems are present in all parts of the world. From the report "The role of
science in mental health" from the Wellcome Global Monitor mentioned that the two most common mental health problems are anxiety, and depression, affect over 400 million people worldwide. Moreover, there are people who experience depression and anxiety around the world up to 19%. As the importance and the number of depression and anxiety, our team focuses to study the relationship between many factors affecting anxiety and depression, and the effective action to alleviate them.

<div class="alert alert-info">
<h3>Project Objectives / Hypothesis Questions:</h3>
</div>

Project Objectives :
* To study the relationship between happiness rank and the rate of people with depression/anxiety.
* To study the relationship between happiness rank and perception of mental health importance.
* To study the factors affecting depression and anxiety problems.
* To study effective action to mitigate depression and anxiety problems.

<div class="alert alert-info">
<h3>Dataset:</h3>
</div>

1. World happiness data

Website Wold Happiness Report (2015 - 2020) : https://worldhappiness.report/

2. Wellcome Global Monitor 2020: Mental health

Website Wellcome : https://wellcome.org/reports/wellcome-global-monitor-mental-health/2020

3. World Mental health statistic data

Website Our world in data : https://ourworldindata.org/mental-health#licence

<div class="alert alert-info">
<h3>Exploratory Data Analysis (EDA):</h3>
</div>

#### Part 1 : Explore happiness rank and the rate of people with depression/anxiety.

In our perception, if people are happy, the rate of depressed or anxious people should be low. To prove it, we use the data from the World happiness report that ranks happiness for each country worldwide to find the relationship with the rate of people with depression/anxiety. 

Question 1:

What are the twenty countries in the top range and in the poorest happiness rank in the world during 2015-2020? 

From exploring the happiness score from 2015-2020 to rank the countries that are in the twenty-top range in the world during 2015-2020, the result is shown below.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/c624d971-a311-489e-a4fa-3787058ca531)

The twenty countries in the poorest hapiness rank in the world during 2015-2020 are shown below.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/65a7fd43-9be5-4a02-96e7-8fde7209e5c7)

Question 2 :

How is the relationship between happiness rank and the rate of people with depression and anxiety ? 

We expect that there are depressed  and anxious people in high happiness countrie rank. As the result of question 1, the additional question is "How is the relationship between happiness scores and the number of people with depression and anxiety? Is a higher happiness score resulting in more depression and anxiety people as our expectation?

To answer the question, we select the countries in the most top-rank and the most poorest-rank happiness scores to find the depression and anxiety rates, then compare them with the worldwide rate. The analysis is coeval (2015-2019).

The countries in the most top-rank from the question 1 include...
1. Finland
2. Denmark
3. Switzerland
4. Norway
5. Netherlands
6. Canada
7. New Zealand
8. Sweden
9. Australia
10. Austrai

The countries in the poorest-rank from the question 1 include...
1. Tazania
2. Rwanda
3. Zimbabwe
4. Yemen
5. Botswana
6. Malawi
7. Afghanistan
8. Haiti
9. India
10. Liberia

From the graph "Comparison depression rate between the most top-rank and poorest-rank happiness score", it ir noticed that a majority of countries in top-rank happiness score (Green line) have depression rate score lower than worldwide rate. Meanwhile, a majority of countries in poorest-rank happiness score (Yellow line) have depression rate score higher than worldwide rate and higher than top-rank countries.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/133518ee-90e0-451b-9784-89579ec019b5)

Secondly, the relationship between happiness score and anxiety rate was analyzed. The graph "Comparison anxiety rate between the most top-rank and poorest-rank happiness score", it is noticed that a majority of countries in top-rank happiness score (Green line) have anxiety rate score higher than the worldwide anxiety rate. Meanwhile, a majority of countries in poorest-rank happiness score (Yellow line) have anxiety rate scores lower than the worldwide anxiety rate and lower than top-rank countries.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/8378201c-66e5-482e-bf29-5d8632c99dc5)

#### Part 2 : Explore the perception of mental helth importance for well-being among the people in top-rank happiness countries.


In the country that are most top-rank of happiness, how about the perceived importance of mental health
for well-being ? 

To answer this question, we focus on top five happiness countries including....
Finland, 
Denmark, 
Switzerland, 
Norway, 
Netherlands, descending. 

We use Wellcome Global Monitor (WGM) survey 2020 data to study. We count the number of people answered that mental health is ‘more important’, ‘as important’ or ‘less important’ in the question "do you think mental health is more important, as important, or less important than physical health for a person’s wellbeing?" to plot graph.

From graph "Score summary of  Importance of Mental Health For Well-Being survey", we find that people in the two most happiness ranks country, Denmark and Finland, think mental health is important as physical health for a person’s well-being. It indicated that people in more happiness ranks tend to place importance on mental health. However, people in all these countries think mental health is important as physical helth more than less important. It indicates that mental health is important for well-being in the perception of people in top rank happiness countries.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/db0f89ea-3461-4d74-9ea4-6cd180cbb983)

#### Part 3 : Study the factors affecting depression and anxiety problems

Question 3. What are the twenty countries have the highest depression and anxiety rate from  1990 to 2019?

From exploring depression and anxiety rate from 1990 to 2019, the twenty countries have the highest depression and anxiety rate are shown in below list.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/ec5c1f2e-adf3-4520-875a-315d56d9b5f4)

The objective of this part is to study the relationship between the rate of people with depression/anxiety and factors including...

1. Country scale : GDP per capita which gives information about the size of the economy and how the economy is performing.
2. Individaul scale : Individual social support and freedom to make life choice.
4. Gender and Age

##### 1. GDP per capita

Question 4 :

In top countries have the higest depression and anxiety rate from question 3, how is the relationship between the rate and GDP per capita from 2015-2019?

We plot the graphs "Percentage of population with mental illness vs Log GDP per capita" to show the relationship between depression/anxiety rates and GDP per capita of the top countries that have the highest depression and anxiety rate during 2015-2019. The result shows that the relationship between the depression rate and GDP per capita is opposite. In contrast, the anxiety rate and GDP per capita is in the same direction.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/663c049a-1a1e-4ac0-ba69-47bb759060c9)

##### 2. Perception of corruption

Let's study the next factor. We expecte that feeling unfair may be one of the factors affecting mental health. Non-corruption social may lead to a healthy mental. In contrast, spreading corruption in the society and goverment may increase stress among honest people. Therefore, we study the relationship between the rate of people with depression/anxiety and the corruption perception in the society.

Note: Corruption Perception is the national average of the survey responses to two questions in the GWP: “Is corruption widespread throughout the government or not” and “Is corruption widespread within businesses or not?” The overall perception is just the average of the two 0-or-1 responses (Close to 1 value means a high level of corruption.). In case the perception of government corruption is missing, we use the perception of business corruption as the overall perception. The corruption perception at the national level is just the average response to the overall perception at the
individual level. (Reference : World happiness report)

Question 5: 

How is the relationship between the rate of people with depression/anxiety and the corruption perception in society during 2015-2019 ?

We plot the graphs "Depression/Anxiety rate (%) vs Perception corruption (0-1) during 2015-2019" shows the relationship between depression/anxiety rates and corruption perception worldwide during 2015-2019. Obviously, worldwide people perceive that corruption is widespread as a result of the high density data in value > 0.5 of corruption perception (Close to 1 value means a high level of corruption.). However, there is no significant relationship between depression and anxiety rate and corruption perception. No matter the high or low depression and anxiety rate, most people think corruption is widespread in the government and society.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/881e34f4-518e-47f4-8f2c-a58eac0bede0)

##### 3. Social support

We study the relationship between the rate of people with depression/anxiety and the factor in the individual scale, the social support factor.

Note : Social support (or having someone to count on in times of trouble) is the national average of the binary responses (either 0 or 1) to the GWP question “If you were in trouble, do you have relatives or friends you can count on to help you whenever you need them, or not?” Close to 1 value means a high level of social support. (Reference: World happiness Report)


Question 6:

How is the relationship between depression/anxiety rate and social support worldwide during 2015-2019 ?

We plot the grahps ""Depression/anxiety rate (%) vs social support factor (0-1) during 2015-2019" shows the relationship between depression and anxiety rate and social support worldwide during 2015-2019 . The result show that the relationship between the depression rate and social support is opposite. However, there is no significant relationship between the anxiety rate and social support.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/e86e040a-4cba-4334-a42e-e334189dcb3d)

##### 4. Freedom to make life choice 

Freedom to make life choices is also expected to be a factor. It include the right to life and liberty, freedom of opinion and expression or speech, the right to work and education, freedom to choose own gender, and many more. A society where people are discriminated may increase levels of stress among the population and increase poor mental health.

In this section, we explore the relationship between depression and anxiety rates and the freedom to make life choice.

Note : Freedom to make life choices is the national average of responses to the GWP question “Are you satisfied or dissatisfied with your freedom to choose what you do with your life?” (Reference : World happiness report)

Value 1 = Satisfied
Value 0 = dissatisfied

Question 7: 

How is the relationship between depression/anxiety rate and freedom to make life choices worldwide during 2015-2019?

We plot the graphs "Percentage of population with mental illness vs Freedom to make life choices (2015-2019)"shows the relationship between depression and anxiety rates and freedom to make life choice scores worldwide during 2015-2019. 

As a result of the high density data in value > 0.5 of freedom to make life choice score (Close to 1 value means a high level of freedom to make life choice), it idicate that most worldwide people have a sense of freedom to make life decisions.
However, there is no significant relationship between depression/anxiety rate and the score. In some countries where people are satisfied with life decisions have depression and anxiety rates higher than lower satisfaction country.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/94aa2fdc-c326-43ac-bd0e-c4dc05572722)

##### 5. Gender and Age
Gender and age may relate to depression and anxiety. From our experience, women tend to overthinking. To prove it, we compare the rate of people with depression/anxiety between males and females.

Question 8:

 What is the gender that has more rate of depression and anxiety worldwide during 2015-2019?

 From a graph "Average percentage of population with mental illness vs Gender,2015-2019", women with both mental health problems are higher than men obviously.  

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/d508b7d4-2d4c-4ec6-b0f3-388c0930b337)




 What about age? Among the young, teenage, mature, and elder, what is the age range that tends to face depression and anxiety? Responsibilities or hormones at each age may affect mental health. To prove it, we explore the percentage of people in each age range and gender who experience depression and anxiety worldwide.

We use statistical data from Wellcome Global Monitor (WGM) survey 2020 in question identifying the age range when people first felt anxious/depressed.

Question 9: 

What are the age range and gender that most people experience depression/anxiety?

Most people in both genders begin to experience depression/anxiety at the age range between 13 - 29 years. The young, age range less than 13 years old, have the least people with depression/anxiety.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/03662127-b15f-4961-8323-320b3293426c)

#### Part 3 : How people manage anxiety or depression

The objective of this part is to study the most common actions taken to alleviate anxiety or depression and the effective actions in top contries having the highest depression and anxiety rate from question 3. including Portugal, Iran, Brazil, Uganda, Lebanon , New Zealand, Greece, Ireland, Switzerland, and Netherlands.

For this part, we use Wellcome Global Monitor (WGM) survey 2020 data to study.

Question 10:

What is the most common action taken to alleviate anxiety or depression and what is the effective action?

We count the number of people who choose each action and plot graph "Common actions taken to alleviate anxiety or depression".We find that most people prefer to talk to friends and family and refuse to engage in religious/spiritual activities when anxious/depressed.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/49e5cd74-a8bb-46cf-b50a-2dec6ca0855f)

In addition, we study the effective actions to alleviate anxiety or depression. We also count the number of people choosing level of helpfulness for each action. We find that most people think spending time in nature or outdoor is the most effective way to mitigate depression and anxiety. The somewhat helpful action is talking to friends and family which most people prefer to choose it at first action to alleviate anxiety or depression. It is surprising, that most people think that taking prescripted medication is not helpful.

![image](https://github.com/SiriwanIm/Mini_Project_5001/assets/104783723/7da98771-59f7-4342-9788-f487c9e00b01)

<div class="alert alert-info">
<h3>Key Findings:</h3>
</div>


* Low rate of people with depression in high happiness rank countries when compare with worldwide rate.
* High rate of people with anxiety in high happiness rank countries when compare with worldwide rate.
* People in high-happiness rank countries tend to think that mental health is important for well-being. In higher happiness rank, there are more people think it is importate.
* The relationship between the rate of people with depression and GDP per capita : Increasing GDP, Decreasing depression rate.
* The relationship between the rate of people with anxiety and GDP per capita : Increasing GDP, Increasing anxiety rate.
* Most worldwide people perceive the high corruption level in government and society even though there is no significant relationship between perception of corruption and mental health rate.
* The relationship between the rate of people with depression and social support: Increasing social support, Decreasing depression rate.
* Most worldwide people think they have the freedom to make life choices.
* The rate of females with depression and anxiety is higher than males.
* People in the age range between 13 - 29 years old tend to begin experience depression and anxiety.
* Most people choose to talk to friends and family when suffering from depression and anxiety but refuse to engage in religious/spiritual activities.
* Spending time in nature/the outdoors is an effective action that most people take to mitigate depression and anxiety.

  <div class="alert alert-info">
<h3>What’s Next / Recommendation:</h3>
</div>

* Improve the economy to reduce the rate of depression people.
* Academy and family should help to prevent or mitigate depression and anxiety among teenagers.
* Mental health talking should be normalized. People should open their minds and support their intimates who suffer from mental health problems.
* Increase green space and nature in the cities to mitigate mental health problems.











