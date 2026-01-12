# Food Accessibility in Nigeria in 2025

![Food-insecurity](https://github.com/user-attachments/assets/6b94064a-419b-4ace-808f-0281e94262c5)

## Project Overview

This is a report made to understand the level of food insecurity in Nigeria across Fifteen (15) states. Although this analysis was not of the entire population in each of these states, the total respondents from each of these Fifteen (15) states played an instrumental role in understanding the impact of food insecurity in their states. It provides insights into their average monthly expenses, their individual food situation as compared to last year, the number of meals they eat per day, and their suggestions on what will make it easier to access affordable and healthy food in Nigeria.

## Motivation

My motivation stemmed from the increase in the cost of foodstuffs, and it made me just imagine how others are also coping and to what extent, which was what brought about the number of meals eaten per day. More than the empathy and the food price inflation, I wanted to use my skills to explain that and also keep others informed by bringing awareness through sharing my report online. Initially, I thought, would it matter, as some people are being affected by the cost of food while others are doing pretty well, but yet I still believed that bringing more eyes to see can increase awareness of these silent struggles. It was a personal project I gathered, and I am glad I did.

## Dataset Description

The data were responses that were gotten via Google Forms, which involved me creating a Google Form and sharing it on my social media platforms to get as many responses as possible. Unfortunately and fortunately, I was only able to gather Fifty-Three (53) responses from 15 different states in Nigeria, which include Ekiti, Oyo, Lagos, Osun, Ogun, Enugu, Ondo, Anambra, Edo, FCT (Abuja), and Kaduna States.

The Google Form was centered on short and important questions, as I did not want to cause the respondents to be tired and also needed quality responses, which was what gave rise to these five (5) questions asked:

1. Which state do you live in?
2. On average, how much do you spend on food monthly?
3. How many meals do you eat per day?
4. What do you think would make it easier for you as a Nigerian to access affordable and healthy food?
5. Compared to last year, how would you describe your current food situation?

## Data Preparation (ETL)

* The data was automatically linked to a Google Sheet, where I inspected the data for accuracy and also had to clean the data due to inconsistencies and some errors.
* After which I connected this source to Power Query for better transformation and omitted further cleaning on Google Sheets.
* Loading into Power BI followed, which caused me to create a single measure, *Total Respondents*, as the data was mainly categorical data with just a single column of numerical data.
* Creating this single measure helped slice it through the other questions, such as *How many meals do you eat per day*, and literally all the columns, as it gave me numerical insights into the numbers of each category in each question or section.

### Measure Used

A single measure was used below throughout this analysis:

```dax
Total Respondents =
COUNTROWS
        ('Form Responses 1')
```

## Analysis & Key Insights

* Total respondents were Fifty-Three (53).
* The responses came from Eleven (11) states amongst the Thirty-Six (36) states in Nigeria.
* The responses from the Eleven (11) states, from the highest to the lowest total number of respondents, were Ekiti, Oyo, Lagos, Osun, Ogun, Enugu, Ondo, Anambra, Edo, FCT (Abuja), and Kaduna States, respectively, and their numbers can be seen via the visual below.


<img width="1331" height="768" alt="Screenshot (239)" src="https://github.com/user-attachments/assets/add035b0-1af4-4b06-ae05-b93f79219cea" />


* According to the responses, half of the respondents say the food situation has slightly worsened, with Twenty-Six(26) people approving this out of the 53 respondents, while Two(2) respondents say it has been much better.
* According to the data gathered, the highest response, which was 40%, says that they spend at least Thirty thousand(30,000) naira on food monthly, which is still much for respondents who were mostly students.
* Out of the total respondents, only 9% of them eat three times daily, and 47% of the respondents eat variably, which means they might eat just once, twice, thrice, or more than thrice.
* According to the responses, 62% suggest a major way to make food accessible is by regulating prices and reducing food inflation.

## Tools Used

* Google Forms
* Google Sheets
* Power Query
* Power BI

## Challenges & Limitations

* A major challenge I faced was gathering this data, which is why I stated above that "unfortunately and fortunately" I was able to gather Fifty-Three (53) responses, but I will lean more into fortunately because many people are usually discouraged from filling Google Forms as they believe it will consist of very lengthy questions. This was the most challenging part of this analysis, as I had to personally and persuasively urge people to help me by filling the form and even go as far as reducing the questions to just five (5) based on the demands of the majority who opened and attempted the form. So, Fifty-Three (53) responses was actually good.

* Another challenge I faced was data cleaning. This was due to the fact that I had to delete Eleven (11) responses because I had a total of Thirty-Six (64) responses, but after the first Eleven (11) respondents whose data was eventually deleted, I was informed to reduce the questions, which eventually got me Fifty-Three (53) responses. Some other cleaning had to be done with the amounts as a result of spaces and some invisible characters.

* An obvious limitation is limited data. I strongly believe having more data across the entire 36 states in Nigeria, and even more responses from the Eleven (11) states I was able to gather, would have strengthened my analysis, but I am grateful.

* I would admit that demographic data, maybe more personal data, and even regions within each state would have also gone a longer way. This was one thing I learnt as I began my analysis.

## Recommendations

* Truth to be told, during the process of gathering and analyzing this data, it was to show those at the seats of power to make a change—those in finance, transportation, agriculture, and other related sectors—but also to every individual who believes in the betterment of this country and has empathy for those who are truly affected, like those in the northern states, because we cannot continue to wait for our leaders. Amongst ourselves, we can make society better in our own little ways.

* Just as the majority of the responses, I strongly support price regulation on food, as it would go a long way in making food more affordable to those who are majorly affected by food inflation. It is sad to even say that here in Lagos I have come across traders who intentionally exploit others even when others are not doing the same. This is just to say that we ourselves wrong ourselves, and we can do better. Everyone wants to make profit, but we should desist from cheating others for our gain. This is highly linked to one of the suggested solutions stated, which is transportation cost reduction through fuel price reduction. I believe all of these are very intertwined and cannot be done in a day, but awareness like this is important to allow our leaders understand they are tryiing and can still do better.

* It is high time we, as Nigerians, intentionally invest in agriculture. By doing this, it will reduce the cost of importation, and individuals in various communities can come together to start farming. Also, cash transfer support and food-sharing initiatives can be given to those truly in need to make food provided for them in their homes.

* By doing all these, I believe our monthly expenses spent on food, the number of meals we eat per day, and several other factors would change positively.

## How to View This Project

You can view this project by downloading the file below:

[Food Accessibility in Nigeria in 2025..pdf](https://github.com/user-attachments/files/24331247/Food.Accessibility.in.Nigeria.in.2025.pdf)

## About the Analyst

I leverage data to create impactful solutions that support sustainable growth. I am particularly passionate about driving progressive results in healthcare, especially within public health, and I also have a strong interest in digital health.

### You can connect with me on LinkedIn:

[https://www.linkedin.com/in/rukayat-olanrewajuabimbola/](https://www.linkedin.com/in/rukayat-olanrewajuabimbola/)

