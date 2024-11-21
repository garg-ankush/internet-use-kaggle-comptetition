- Any PCIAT columns don't exist in test.
- PCIAT total is positiviely correlated with sii - they took the PCIAT total and discretized it into categories.
- PCIAT reports "how often" type questions. The higher the total, the higher the sii score.
- Alot of 0s, some 1s, some 2s and very few 3s.
- Younger kids under the age of ~12 have a lot more records compared to older kids. There also seems to be a pattern here - kids above 10, seem to be equally distributed among the sii field, whereas younger kids have a lot more 0.0. This may indicate that younger kids listen to their parents more. If it's age related, this may need two models based on age.
- No pattern in sex
- CGAS centers around the middle. So basically, few childeren are on the extremes (completely independent) but most are dependent. Under 12 are more concetrated, which makes sense. Over 12 seem to be spread out a bit more.
- BMI - seems to be going up as age goes up. Alot more 1,2,3 here compared to under 12 aged kids. Some kids over the age of 12 fall into the obese category. Few kids have 0s for BMI.
- Activity level doesn't have any pattern with age and sii. 
- Internet use - if you're older than 12, and have a higher internet use, you're likely to be higher sii.

- After the analysis, I think we need to create 2 separate models - kids under 8 and over 8. I think that may result in a better overall model.

['Basic_Demos-Age',
 'Basic_Demos-Sex',
 'CGAS-CGAS_Score',
 'Physical-BMI',
 'BIA-BIA_Activity_Level_num',
 'PreInt_EduHx-computerinternet_hoursday',
 'sii']