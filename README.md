# Food Accessibility in Nigeria in 2025

![Food-insecurity](https://github.com/user-attachments/assets/6b94064a-419b-4ace-808f-0281e94262c5)


## Project Overview

This is a report made to understand the level of food insecurity in Nigeria across 15 states. Although this analysis was not of the entire population in each of these states but the total respondents from each of these 15 states played an instrumental role in understanding the impact of food insecurity in their states. It provides insights into their average monthly expenses, their individual food situation as compared to last year, the number of meals they eat per day and their suggestions on what will make food it easier to access affordable and healthy food in Nigeria.


## Motivation

My motivation stemmed from the increase in cost of foodstuffs and it made me just imagine how others are also coping and to what extent which was what brought about the number of meals eaten per day and more than the empathy and the food prices inflation I wanted to use my skills to explain that and also keep others iformed by bringing awareness by sharing my report online. Initially I thought would it matter as some people are being affected by the cost of food while others are doing pretty well but yet i still believed that bringing more eyes to see can increase the silent struggles. It was a personal project I gathered and I am I did.

## Dataset Description

The data were responses that was gotten via Google Forms which involved me creating a Google Form and sharing them on my Social media platforms to get as many respnses as possible, unfortunately and fortunately I was only able to gather Fifty-Three(53) responses from 15 different states in Nigeria which includes Ekiti, Oyo, Lagos, Osun, Ogun, Enugu, Ondo, Anambra, Edo, FCT(Abuja) and Kaduna States.
The Google Form was centered to be short and important questions, as I did not want to cause the respondents to be tired and also needed responses which was what gave rise to these five(5) questions asked
1. Which state do you live in?
2. On average, how much do you spend on food monthly?
3. How many meals do you eat per day? 
4. What do you think would make it easier for you as a Nigerian to access affordable and healthy food?
5. Compared to last year, how would you describe your current food situation? 

## Data Preparation (ETL)

- The data was automatcally linked to a Google Sheet where I inspected the data for accuracy,also had to clean the data due to inconsistencies and some errors 
- After which I connected this source to Power Query for a better transformation and ommitted cleanings on Google Sheets
- Loading to Power Bi followed which caused me to create a single measure - Total Respondents - as the data was mainly a categorical data and just a single column of numerical data 
- Creating this single measure helped slice it through the other quetsions such as How many meals do you eat per day and literally all the columns as it gave me numerical insights into the numbers of each category in each question or section

### Measure Used
A single measure was used below through out this analysis :

```dax
Total Respondents =
COUNTROWS
        ('Form Responses 1')
```

## Analysis & Key Insights

- Total Respondents were Fifty-Three(53)
- The responses came from Eleven(11) states amongst the Thirty-Six(36) states in Nigeria 
- The responses from the Eleven(11) states from the highest to the lowest total number of respondents were Ekiti, Oyo, Lagos, Osun, Ogun, Enugu, Ondo, Anambra, Edo, FCT(Abuja) and Kaduna States with respectively and their numbers can be seen via the visual below

<img width="1331" height="768" alt="Screenshot (239)" src="https://github.com/user-attachments/assets/add035b0-1af4-4b06-ae05-b93f79219cea" />

- According to the responses half of the repondents says the food situation has slightly worsened with 26 people approving this out of the 53 respondents with 2 respondents sayng it has been much better
- According to the data gathered the highest responses which was 40% says that they spend at least 30,000 on food monthly which is still much for a respondents who were mostly students 
- Out the total respondents on 9% of them eat three times daily and 47% of the repondents eat variably which means they might eat just once , twice or thrice or more than thrice 
- According to the responses 62% suggest a major way to make food accessible is by regulting the price and reducing food inflation 

## Tools Used

- Google Forms
- Google Sheets
- Power Query
- Power BI

## Challenges & Limitations

- A major challenge I faced was gathering this dat which was why I stated above that "unfortuantely and fortunately" I was able to gather 53 responses but I will lean more into fotunately because many people are usually discoraged to fill Googlr Forms as thry believe it will consist of very lengthy questions, This was the most challenging part of this analysis as I had to personally and persuavively urge people in helping me out in filling the form and even go as far as reducing the questions to just five(5) based on the demands on the mjority who opened attempted the form, so 53 responses was actually good 

- Another challenge I faced will be data cleaning , this was due to the fact that I had to delete 11 reponses because I had a total of 64 reponses but after the first 11 respondents whose data was eventaully deleted I was informed to reduce the questions which eventually got me 53 responses and some other cleaning had to be done with the amounts as a result of spaces and some invisible spaces 

- An obvious limitation is a limted data I strongly believe having more data across the entire 36 states in Nigeria and even more responses from the 11 states I was able to gather would have strengthened my analysis, but I am grateful

- I would admit that demographic data and maybe more personal data and even regions in each of their states would have also gone a longer way, this was one thing I learnt as I began my analysis


## Recommendations

1. Truth to be told when during the process of the gathering and analysis of this data it was to show those at the seats of power to make a change those in the Finance, transportation, agriculture and other related sectors but also to every indidvidual who beleives in the betterment of this country and empathy for those who truly are affected like those in the northern states because we can not continue to wait for our leaders but amongst ourselves we can make a society better in our own little help

2. Just as the majority of the responses I strongly support price regulation on the food would go a long way causing food to be more affordable to those who are majorly affected by food inflation, it is sad to even say that in Lgos here I have come across traders who intentionally exploits others even when others are not doinfg te same this is just to say we oursleves wrong ourseleves, we can do better, everyone wants to make profit but we should desist from cheating others for our gain. This is higly linked to one of the suggestted solution stated which is transportation cost reduction by fuel price reduction. I beleive all of these a very interwined and can not be done in a day but awareness like this is important to allow them understand that our leaders can still do better

## How to View This Project

You can view this project by downloading the file below:

[Food Accessibility in Nigeria in 2025..pdf](https://github.com/user-attachments/files/24331247/Food.Accessibility.in.Nigeria.in.2025.pdf)

## About the Analyst
I leverage data to create impactful solutions that support sustainable growth. I am particularly passionate about driving progressive results in healthcare, especially within public health, and I also have a strong interest in digital health.

### You can connect with me on LinkedIn : https://www.linkedin.com/in/rukayat-olanrewajuabimbola/


