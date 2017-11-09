# Is the Zika virus actually getting worse in the United States or is there false information circulating?

The following information was pulled directly from www.kaggle.com where there is a survey that shows the number of Zika cases per month and by location. Kaggle user, Thiago, created data visualizations that show Zika cases generally getting worse every year for every country. 

![image](https://user-images.githubusercontent.com/32119820/32259045-1cc542b8-be7b-11e7-9673-a2372a1d06d0.png)

![image](https://user-images.githubusercontent.com/32119820/32258671-1f45e044-be79-11e7-9222-a2d767fec4e9.png)

However, Thiago’s generalizations give the audience a wrong impression and is not completely accurate. He is looking too broadly to see if the number of reported cases is increasing every year. He does not look to see if other factors could play a role, which creates a unwarranted fear among people. In addition, reported cases is not accurate as there could be those who feel that they have Zika viruses but are actually experiencing a different virus. If that is the case, the total number of reported cases does not get updated with the new number. 
<br/>

Instead we should be focusing on the number of confirmed cases so that we can be more accurate. We should also split up the data by age groups of 20 years, as shown in the survey. Age could play a critical role to see if Zika is getting worse and it will allow us to take more specific actions. Rather than scaring everyone and not being able to have a call-to-action, we could see if those who are younger tend to be more vulnerable than those who are older and vice-versa. Additionally we want to shift our focus to the United States as that information would affect us closely. 
<br/><br/>

## Project Key Items:
Claim: The Zika virus is not getting worse as stated in the original data visualization <br/>
Audience: Females in the mid-20s to late 30s who are worried about contracting the Zika virus and having birth complications <br/>
Needs: To see evidence that the virus isn't getting out of hand and they have nothing to worry about <br/>
Wants: The virus to subside in areas that they frequently visit or live in <br/>
Fears: The Zika virus is getting worse over time <br/>

---------
## Project Progression:

#### <i>Exploratory Visual:</i>
In the first visual, our goal is to see what the trend is between reported and confirmed case. In the graph we could see that there is generally a larger number of confirmed versus reported cases. It is interesting to see that in January there are a few reported cases but no confirmed cases. This could be an indicator that the symptoms could take a while to appear and the total number of confirmed cases that we see in June could be those who were actually affected in an early month such as February.

![image](https://user-images.githubusercontent.com/32119820/32259122-8fea41b2-be7b-11e7-99e6-c27827b3fe3e.png)

This is visual is good to see that we will need to take a closer look at the reported cases to see if it's actually increasing every month. From a high overview, it looks as though Zika is getting worse as the months progress. However, we still need to view additional factors such as age.
<br/><br/>

#### <i>Data Wrangling:</i>

<br/>

## Prototypes:

<br/>

#### <i>1st Iteration:</i>

![image](https://user-images.githubusercontent.com/32119820/32590330-b873657e-c4ce-11e7-8ba4-809ebbc06282.png)

![image](https://user-images.githubusercontent.com/32119820/32590341-c82b28bc-c4ce-11e7-8f1b-b6fc678a3a2b.png)

In the first chart, it shows a breakdown of the reported Zika cases that came from local (mosquitoes in the area) versus those who contracted Zika while traveling abroad. In that chart it is clear that the increased number of cases are only caused by people traveling to areas with the Zika virus. None of the reported cases come from being bitten by mosquitoes in the United States.
<br/>
In the second chart, we can see that there is no relationship between reported and confirmed cases. People could think that they have the Zika virus and report it, but they might have another virus with similar symptoms. Although the number of reported cases is increasing, there are consistently no confirmed cases in US states in 2016. This allows the audience to believe that they have nothing to worry about since no one in 2016 had the virus.
<br/><br/>

In the next version, I want to reduce the number of variables shown in each graph. It may be too cluttered to see so many variables for the graphs, so I am going to find the standard deviation between reported and confirmed cases.

#### <i>2nd Iteration:</i>

![image](https://user-images.githubusercontent.com/32119820/32528377-92cecb0c-c3e7-11e7-927d-502ea6e0c276.png)

In this version, I took the perentage difference between reported and confirmed cases. In the above chart, we can see that majority of the time there are more reported cases than cofirmed cases in the United States. This allows us to be more at ease because we only really care about the confirmed cases. If there isn't a strong correlation between reported and confirmed cases, then we don't have to worry about Zika being an issue in the United States.



----------


1. Project statement (Motivation, objective, data, project plan)  
2. “Making-of” documentation (Details of your development process, data wrangling steps, your reasoning,  detours, literature, etc.)  
3. Several intermediate visualization prototypes  
4. Final data visualization  
5. Road map with future features/enhancements/features  
6. Showcase video (<90 sec)  

