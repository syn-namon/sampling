# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `3`

Describe the purpose of your survey:
```
The purpose of my survey is to understan how age affects the musing taste and correlation of the age with tendency to like a specific type of music and perceptions of popular music
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: people from 15 to 100 years old.
Sampling frame: public libraries, universities, collegies, social media, comunity organizations (like YMCA, etc.).
Sampling units: individuals from across mentioned places who were selected for the survey.
Samling strategy: The population will be devided into stratas of similar age (15 - 20, 21 - 25, 26 - 30, 31 - 40, 41 - 50, 51 - 60, 61 - 70, 71 - 80, 81 - 90, 91 - 100) and analyzed by these stratas with randomly selected individuals within each strata.
``` 

Your 5-10 question survey:
```
1. How old are you?
2. What genre of music you are into right now?
3. Why do you like it?
4. How do you feel about pop-music these days?
5. Do you think your music taste changed over years?
6. If the answer to the question 5 was yes, please tell us what type of music you liked 5, 10, 20 years ago?
7. What artist or genre of music remains your favourite one over years?
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: two-stage sampling design: first, stratification method for creating stratas based on the areas, then the information is collected from one randomly selected household member aged 15 or older, and proxy responses are not permitted
2. Sample size: approximatively 50,000 units
3. Target population: people aged 15 years and over living in private households in Canada, excluding residents of the Yukon, Northwest Territories and Nunavut and full time residents of institutions. 
4. Sampling frame: the survey uses a frame that combines landline and cellular telephone numbers from the Census and various administrative sources with Statistics Canada's dwelling frame. Records on the frame are groups of one or several telephone numbers associated with the same address.
5. Survey mode(s): telephone interview and electronic questionnaire.
6. Timeline: the data was processed from 2018-09-04 to 2018-12-28 and published in January 2021.
7. Response rate: 41.9%
8. Weights: weights were used to 1)adjust for the 'rejecting' of a proportion of respondents that are not volunteers; 2)adjustment of weighted income distribution of GVP matched the 2017 CIS distribution by province; 3)bootstrap weights have been created for the purpose of design-based variance estimation; 4)estimates based on the survey data are also adjusted (by weighting) so that they are representative of the target population with regard to certain characteristics (each month we have independent estimates for various age-sex groups by province); 5)survey estimates were adjusted to account for non-response cases; 6)survey estimates were adjusted to represent all persons in the target population, including those not covered by the survey frame.
9. Data processing: Data was collected directly from survey respondents either through an electronic questionnaire or through CATI (computer assisted telephone interviewing). Then it was transformed into public use microdata file (PUMF) to help users access and manipulate the the data for the further processing and analysis.
10. Cleaning, imputation, etc: 1)Except in a few cases, all imputations were made using donor records selected through a score function. 2)Where donor imputation could not be used, mean imputation among a pool of donors was used. 3)Income imputation: income was linked to the tax documentation according to the respondents agreement to link it.
11. Sources of error: sampling error, imperfect coverage and non-response errors, processing error.
12. Limitations, known biases, etc: non-response bias - households without telephones were excluded, undercoverage - only ten provinces were included into target population.
13. Link to documentation and any additional sources used:
https://www150.statcan.gc.ca/n1/en/catalogue/45250011 
https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234 
https://www150.statcan.gc.ca/n1/pub/75-006-x/2021001/article/00002-eng.htm
https://www150.statcan.gc.ca/n1/daily-quotidien/210126/dq210126h-eng.htm

```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
