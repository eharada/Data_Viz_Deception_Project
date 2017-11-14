# Is the Zika virus actually getting worse in the United States or is there false information?

The following information was pulled directly from www.kaggle.com where there is a CDC survey that shows the number of Zika cases per month and by location. Kaggle user, Thiago, created data visualizations that show Zika cases generally getting worse every year for every country. The specific dataset can be found here:

https://www.kaggle.com/thiagoprocaci/zika-cases-by-country/code

![image](https://user-images.githubusercontent.com/32119820/32259045-1cc542b8-be7b-11e7-9673-a2372a1d06d0.png)

![image](https://user-images.githubusercontent.com/32119820/32258671-1f45e044-be79-11e7-9222-a2d767fec4e9.png)

However, Thiago’s generalizations give the audience a wrong impression and is looking too broadly to see if the number of reported cases is increasing every year. However, reported cases is not accurate as there could be those who feel that they have Zika but are actually experiencing a different virus. If that is the case, the total number of reported cases does not get updated with the new reduced number. 

It will be important to validate the fact that Zika isn't getting worse as this is was a rising concern in 2016. Women who contract the virus will have pregnancy complications and newborns will have birth defects. Therefore, if we are able to show that Zika isn't getting worse, then United States can focus their efforts on other diseases that are affecting its citizens on a higher basis.

Instead of looking at only the reported cases, we should also look at confirmed cases to see if there is a one-to-one relationship between reported cases turning into confirmed cases. If there is no relationship, then there is no need to spend more money on Zika. In addition, we will be focusing on the United States as I am making the assumption that our audience are only those who are living in the United States or one of its territories.

<br/>
## Project Key Items:
Claim: The Zika virus is not getting worse as stated in the original data visualization <br/>
Rebuttal: The Zika virus is getting worse over time and we should spend more money on a cure <br/>
Qualifier: The virus is not getting worse in the United States <br/>
Audience: Everyone living in the United States who is afraid of contracting the virus <br/>
Needs: To see evidence that the virus isn't getting out of hand and they have nothing to worry about <br/>
Wants: The virus to subside in areas that they frequently visit or live in <br/>
Fears: The Zika virus is getting worse over time and we need to spend more money<br/>

---------
## Project Progression:

#### <i>Exploratory Visual:</i>
In the first visual, our goal is to see what the trend is between reported and confirmed case. In the graph we could see that there is generally a larger number of confirmed versus reported cases. This could be an indicator that the symptoms could take a while to appear. For example, the total number of confirmed cases that we see in June could be those who were actually affected in an early month such as February.

![image](https://user-images.githubusercontent.com/32119820/32765980-b7950dfa-c8c1-11e7-807e-feb46021bd20.png)

This visual is good because we can see that we will need to take a closer look at the reported cases to see if it's actually increasing every month. From a high overview, it looks as though Zika is getting worse as the months progress. However, the exploratory data looks at the total values rather than averages, so the trend could look worse than it actually is.
<br/>

#### <i>Data Wrangling:</i>

In Jupyter, the data needed to be cleaned up for typos. For example, Pennsylvania had extra characters for some of the data. This could be due to how the data was converted from CDC. In addition, we will remove certain columns that we do not need such as the data_field_code, time_period, and time_period_type.

## Prototypes:
#### <i>1st Iteration:</i>

![image](https://user-images.githubusercontent.com/32119820/32590330-b873657e-c4ce-11e7-8ba4-809ebbc06282.png)

![image](https://user-images.githubusercontent.com/32119820/32590341-c82b28bc-c4ce-11e7-8f1b-b6fc678a3a2b.png)

In the first chart, it shows a breakdown of the reported Zika cases that came from local (mosquitoes in the area) versus those who contracted Zika while traveling abroad. In that chart it is clear that the increased number of cases are only caused by people traveling to areas that is prominant with Zika. None of the reported cases come from being bitten by mosquitoes in the United States.

In the second chart, we can see that there is no relationship between reported and confirmed cases. People could think that they have the Zika virus and report it, but they might have another virus with similar symptoms. Although the number of reported cases is increasing, there are consistently very few confirmed cases in US states in 2016. This allows the audience to believe that they have nothing to worry about since no one in 2016 had the virus.

In the next version, I want to reduce the number of variables shown in each graph. It may be too cluttered to see so many variables for the graphs, so I am going to see what percent of cases are reported and what percent are confirmed. This will allow the audience to easily compare the two categories.

#### <i>2nd Iteration:</i>

![image](https://user-images.githubusercontent.com/32119820/32765904-6c56f7e0-c8c1-11e7-84bf-47fa62dabe88.png)

In this version we are looking at the difference between reported and confirmed cases. In the above chart, we can see that every month there are more reported than cofirmed cases in the United States. This allows us to be more at ease because we only really care about the confirmed cases. This addresses the audience's fears that the Zika virus is spreading quickly and that we need to take action immediately. 

In the next version, I am going to show two charts. One that follows the claim that Zika is getting worse in the United States and another that shows that Zika is not getting worse. This will allow us to see how one data visualization can be manipulated to tell a completely different story. Despite having the same exact data, we are able to show that Zika is getting worse and that Zika is not getting worse. Both will take the average reported and confirmed number of cases rather than the sum. In the survey data, there were a lot rows that had zero reported/confirmed cases. Therefore, we will want to even out the data and view the averages in both versions.

----------

## Final Version:

### Claim One: Zika is getting worse in the United States and we should put more focus on finding a cure

![image](https://user-images.githubusercontent.com/32119820/32765742-c5f88eb8-c8c0-11e7-90bc-21d1f82b0ee7.png)

The chart shows reported and confirmed cases getting worse as the months progress. Although the number of confirmed cases is less than the number of reported cases, we still want to pay attention to the total number of cases per month. This signifies that the CDC should focus more efforts towards the Zika virus in order to avoid a massive outbreak in a few months.

### Claim Two: Zika is not getting worse in the United States and the CDC should take no further actions

![image](https://user-images.githubusercontent.com/32119820/32766412-b5919a44-c8c3-11e7-924f-76bb9447f40f.png)

The chart above shows that although the number of average cases in increasing, we haven't seen a huge spike since February 2016. In addition, majority of the cases each month are reported instead of confirmed. This indicates that there is no direct correlation between reported and confirmed cases. Therefore, United States has nothing to worry about because the number of confirmed cases is significantly lower than the number of reported cases. More often than not, people feel Zika-like symptoms but are often feeling symptoms from another virus.

In addition to our findings, the CDC website (https://www.cdc.gov/zika/reporting/case-counts.html) backs up our claim and shows updated information on the status of Zika cases. 

![image](https://user-images.githubusercontent.com/32119820/32713569-ab48021e-c7fe-11e7-8965-79de7aad1594.png)

In CDC's chart, it is visible that Zika is in fact not getting worse. After a large increase in July 2016, the number of Zika cases has been vastly decreasing and there are no significant cases during this past year. Because this is confirmed with the CDC, the United States has nothing to worry about as this is a trusted/reliable source. Therefore, no further actions need to be taken as we can reduce our current funding for Zika virus. Instead, we should allocate those resources elsewhere to other more prominant diseases.

-----------
## Future Enhancements

In future versions, I would like to include the following:
1. Get more data on Zika virus in the United States. Right now the survey is limited to only having confirmed cases in the Virgin Islands. If there are more people with confirmed cases in the United States, we'll want to include that in our findings.<br/>
2. Get more specific data on reported cases to include age. This will allow us to see whether age plays a role in the number of Zika cases. If it does, then we would be able to take more specific actions.<br/>

---------
*Make sure to add class concepts
*add jupyter notebook
*add tableau public links
4. Final data visualization 
5. Road map with future features/enhancements/features 
6. Showcase video (<90 sec) 

