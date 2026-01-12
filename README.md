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
- According to the 

## Tools Used

- Google Forms
- Google Sheets
- Power Query
- Power BI

## Challenges & Limitations

## Recommendations

## How to View This Project

You can view this project by downloading the file below:

[Food Accessibility in Nigeria in 2025..pdf](https://github.com/user-attachments/files/24331247/Food.Accessibility.in.Nigeria.in.2025.pdf)

## Conclusion

## About the Analyst
I leverage data to create impactful solutions that support sustainable growth. I am particularly passionate about driving progressive results in healthcare, especially within public health, and I also have a strong interest in digital health.

### You can connect with me on LinkedIn : https://www.linkedin.com/in/rukayat-olanrewajuabimbola/


