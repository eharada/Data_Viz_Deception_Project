# Is the Zika virus actually getting worse in the United States or is there false information?

The following dataset was pulled from www.kaggle.com. This specific dataset contains a CDC survey that displays the number of Zika cases over time and separated by geography. Kaggle user, Thiago, created data visualizations that show Zika cases generally getting worse as the months progress for each country. The specific dataset can be found here:

https://www.kaggle.com/thiagoprocaci/zika-cases-by-country/code

A sample of Thiago's data visualizations is below:

![image](https://user-images.githubusercontent.com/32119820/32259045-1cc542b8-be7b-11e7-9673-a2372a1d06d0.png)

![image](https://user-images.githubusercontent.com/32119820/32258671-1f45e044-be79-11e7-9222-a2d767fec4e9.png)

However, Thiago’s generalizations may give the audience a wrong impression as it is looking too broadly. His visuals only focus on  reported cases rather than confirmed cases. However, reported cases are not completely accurate as there could be people who feel they have Zika but are actually experiencing a different virus. If that is the case, the total number of reported cases does not get updated after with the new reduced number. 

It will be important to validate the fact that Zika isn't getting worse as this was a rising concern in 2016. Women who contract the virus will have pregnancy complications and newborns will have birth defects. Therefore, if we are able to show that Zika isn't getting worse, then United States can focus their efforts on other diseases that are affecting its citizens.

Instead of looking at only the reported cases, we should also look at confirmed cases to see the total number has a positive trend. If confirmed cases aren't increasing as quickly as Thiago's chart suggests, there is no need to spend more money on Zika. In addition, the focus will be on the United States as I am making the assumption that our audience is only those who are living in the United States or one of its territories.
<br/>

## Project Key Items:
Claim: The Zika virus is not getting worse as stated in the original data visualization <br/>
Rebuttal: The Zika virus is getting worse over time and we should spend more money on a cure <br/>
Qualifier: The virus is not getting worse in the United States <br/>
Audience: Everyone living in the United States who is afraid of contracting the virus and having long-term consequences <br/>
Needs: To see evidence that the virus isn't getting out of hand and they have nothing to worry about <br/>
Wants: The virus to subside in areas that they frequently visit or live in <br/>
Fears: The Zika virus is getting worse over time and we need to spend more money <br/>

---------
## Project Progression:

#### <i>Exploratory Visual:</i>
In the first visual, our goal is to see what the trend is between reported and confirmed case. In the graph we could see that there is generally a larger number of confirmed cases than reported cases. This could be an indicator that the symptoms could take a while to appear. For example, the total number of confirmed cases that we see in June could be those who were actually affected in an early month such as February. However it could also be an indicator that majority of the cases aren't verified, so Zika is not getting worse.

![image](https://user-images.githubusercontent.com/32119820/32765980-b7950dfa-c8c1-11e7-807e-feb46021bd20.png)

This visual is good because it shows that that number of reported and confirmed cases is generally increasing over time. It makes it easy for the audience to see if their fears are a reality. However, we must be cautious as the exploratory data includes the total values rather than averages. In addition, it may include outliers that will need to be excluded. Because of this, the trend could look worse than it actually is.
<br/>

#### <i>Data Wrangling:</i>

In the original survey spreadsheet, the data needed to be cleaned up for typos. For example, Pennsylvania had extra characters for some of the entries. This could be due to how the data was converted from CDC. In addition some rows had empty cells for the value column, so those entries were dropped. If we were to keep those rows, then it would skew our data in which the average number of cases would be lower. Lastly, we will remove certain columns that we do not need such as the data_field_code, time_period, and time_period_type.

## Prototypes:
#### <i>1st Iteration:</i>

![image](https://user-images.githubusercontent.com/32119820/32590330-b873657e-c4ce-11e7-8ba4-809ebbc06282.png)

![image](https://user-images.githubusercontent.com/32119820/32590341-c82b28bc-c4ce-11e7-8f1b-b6fc678a3a2b.png)

In the first chart, it shows a breakdown of the reported Zika cases that came from local mosquitoes in the area versus those who contracted Zika while traveling abroad. In that chart it is clear that the increased number of cases are only caused by people traveling to areas that are prominant with Zika. None of the reported cases are from being bitten by mosquitoes in the United States. Therefore, the best solution would be to stop all plans to travel to areas with high reports of Zika virus.

In the second chart, it is visible that there is no relationship between reported and confirmed cases. People could think that they have the Zika virus and report it, but in reality they might have another virus with similar symptoms. Although the number of reported cases is increasing, there are consistently very few confirmed cases in US states in 2016. This allows the audience to believe that they have nothing to worry about since no one confirmed they had the virus in 2016.

Both charts have the average number of cases rather than the sum. This allows us to normalize the data and see a more realistic point of view.

In the next version, I want to reduce the number of variables shown in each graph. It may make the chart cluttered and may be confusing to follow. Therefore I am going to combine the variables and compare the percent of cases that are reported with the percent that are confirmed. This will allow the audience to easily compare the two categories.

#### <i>2nd Iteration:</i>

![image](https://user-images.githubusercontent.com/32119820/32765904-6c56f7e0-c8c1-11e7-84bf-47fa62dabe88.png)

In this version we are looking at the difference between reported and confirmed cases. In the above chart, we can see that every month there are more reported than confirmed cases in the United States. This allows us to be more at ease because we only really care about the confirmed cases. This addresses the audience's fears that the Zika virus is spreading quickly and that we need to take action immediately. 

In the next iteration I am going to show two charts. One that follows the claim that Zika is getting worse in the United States and another that shows that Zika is not getting worse. This will allow us to see how one data visualization can be manipulated to tell a completely different story. Despite having the same exact data, we are able to show multiple viewpoints.

----------

## Final Version:

### <i> Claim One: Zika is getting worse in the United States and we should put more focus on finding a cure </i>

![image](https://user-images.githubusercontent.com/32119820/32871070-d258a4a8-ca33-11e7-87a0-f6652a4086ff.png)

The chart shows reported and confirmed cases getting worse as time progresses. Although the number of confirmed cases is less than the number of reported cases, we still want to pay attention to the total number of cases per month. This signifies that the CDC should focus more efforts towards the Zika virus in order to avoid a massive outbreak in a few months.

### <i> Claim Two: Zika is not getting worse in the United States and the CDC should take no further actions </i>

![image](https://user-images.githubusercontent.com/32119820/32871053-c05513a4-ca33-11e7-93d2-c257c43118ba.png)

The chart above shows that although the number of average cases in increasing, we haven't seen a huge spike since February 2016. In addition, majority of the cases each month are reported instead of confirmed. This indicates that a majority of the time, there are false reports of Zika. Therefore, United States has nothing to worry about because the number of confirmed cases is significantly lower than the number of reported cases. More often than not, people feel Zika-like symptoms but are actually feeling symptoms from another virus.

In addition to our findings, the CDC website (https://www.cdc.gov/zika/reporting/case-counts.html) backs up our claim and shows updated information on the status of Zika cases. 

![image](https://user-images.githubusercontent.com/32119820/32713569-ab48021e-c7fe-11e7-8965-79de7aad1594.png)

In CDC's chart, it is visible that Zika is not getting worse. After a large increase in July 2016, the number of Zika cases has been vastly decreasing and there are no significant cases during 2017. Because this is confirmed with the CDC, the United States has nothing to worry about as this is a trusted/reliable source. Therefore, no further actions need to be taken and we can reduce our current funding for Zika virus. Instead, we should allocate those resources elsewhere to other more prominant diseases.

## Tableau Public Links:
#### Zika is getting worse: https://public.tableau.com/profile/elena.harada#!/vizhome/DeceptionProject/ProDashboard?publish=yes
#### Zika is not getting worse: https://public.tableau.com/profile/elena.harada#!/vizhome/DeceptionProject/ConDashboard?publish=yes

-----------
## Future Enhancements

In future versions, I would like to include the following:
1. Get more data on Zika virus in the United States (specifically the states). Right now the survey is limited to only having confirmed cases in the Virgin Islands. If there are more people with confirmed cases in the United States, we'll want to include that in our findings.<br/>
2. Get more specific data on reported cases to include age. This will allow us to see whether age plays a role in the number of Zika cases. If it does, then we would be able to take more specific actions.<br/>
3. Include data on more current months (second half of 2016 and all of 2017). Right now the survey only contains data on the first half of 2016 so the information could be a bit outdated.

---------

*Add a Showcase video (<90 sec)

