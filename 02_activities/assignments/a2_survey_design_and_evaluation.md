# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey.
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

The number of your chosen topic: `#1`

Describe the purpose of your survey:
```
The goal of this survey is to figure out why many lower-level employees are leaving the company. By collecting feedback, we can highlight specific problems, like low pay or poor management, and recommend changes to make employees happier so they stay with the company longer.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target Population: current entry- or lower-level employees, plus people who held those jobs but left within the last six months.
Sampling Frame: the Human Resources (HR) department's list of all active employees and records for people who recently quit.
Sampling Units: each individual person who is either an active employee or a recent former employee.
Overall Sampling Strategy: I will use a Stratified Random Sample. I'll divide the population into groups (strata) based on which department they work in (like Sales, Engineering, etc.) and whether they are current or former employees. Then, I'll randomly pick a certain number of people from each group. This makes sure I get feedback from every major department and from the people who are currently here as well as the people who left.
```

Your 5-10 question survey:
```
1. Overall, how happy were/are you with your job experience here? (Rate 1 to 5: 1=Very Unhappy, 5=Very Happy)
2. How satisfied were/are you with your pay (salary/wages) and benefits? (Rate 1 to 5: 1=Very Unhappy, 5=Very Happy)
3. Do you feel you have/had good chances for promotion or moving up in your career here? (Rate 1 to 5: 1=Not at all, 5=Completely)
4. How helpful and effective is/was your direct manager? (Rate 1 to 5: 1=Very Poor, 5=Very Good)
5. What is the single most important thing the company should change to keep more lower-level employees? (Write your answer)
6. [If you recently left the company]: What was the main reason you quit? (Select one: Pay/Better Offer / No Growth / Manager Issues / Work-Life Balance / Company Culture / Other)

```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: this was a multi-step, probability-based sample where everyone in the target group had a known chance of being selected. They used the stratification process to make sure the sample covered different parts of the country evenly.
2. Sample size:	13,010 people were interviewed
3. Target population: all people in Canada, aged 15 and older, who live in one of the ten provinces, but not the ones that live in institutions like hospitals or nursing homes or military bases
4. Sampling frame: the sample was selected using the most recent list of households from the Labour Force Survey (LFS) sampling frame. Think of this as the main directory or list they used to pick the houses to call.
5. Survey mode(s): data was collected mainly over the phone using Computer-Assisted Telephone Interviewing (CATI). In some areas, they used Computer-Assisted Personal Interviewing (CAPI), which means an interviewer met the person face-to-face.
6. Timeline : the interviewers collected the data over a full year, from January 2018 through December 2018
7. Response rate: half of the eligible people contacted actually completed the survey: the rate was 50.6%.
8. Weights: statistical weights were applied to the data. These are adjustment factors used to make the 13,010 people who responded accurately represent the millions of people in the entire Canadian population. They help correct for people who didn't respond or groups that were missed by the sampling frame.
9. Data processing: involved all the steps to turn raw answers into usable data, including coding (turning text answers into categories), editing (checking for mistakes), and imputing (filling in missing information).
10. Cleaning, imputation, etc: imputation was specifically used to fill in missing values, especially for money-related questions like income and donation amounts. They used other records with similar characteristics (donor imputation) or general rules (deterministic imputation) to fill in the blanks.
11. Sources of error: Besides the usual sampling error (since it's only a sample, not everyone), the survey had non-sampling errors. These include: people not answering (non-response error), the list not covering everyone (coverage error), and mistakes in how questions were asked or answered (measurement error).
12. Limitations, known biases, etc: A few known issues are: people might over-report positive things like volunteering (social desirability bias), people might misremember how much they gave or volunteered (recall bias), and the results don't apply to people living in the territories or institutions.
13. Link to documentation and any additional sources used: The information was derived from the provided document: 2018 General Social Survey on Giving, Volunteering and Participating (GSS 33) Public Use Microdata File (PUMF) User Guide.
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 19/10/2025`
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
