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

1. Sample type : This survey is a multi-stage startification based on Canadian Census- 2021. 

2. Sample size: The total sample size for the SGVP is 80,000 individuals (60,000 regular sample, 20,000 oversample). 

3. Target population: Individuals 15 years of age and over in Canada's ten provinces. Excluded: Residents of the Yukon, Northwest Territories, and Nunavut, as well as full-time residents of institutions.

4. Sampling frame: The sampling frame was the Canada Child Benefit (CCB) file, supplemented by the Census of Population frame where CCB data was unavailable. The CCB file is an administrative data source that provides excellent coverage of Canadian households.

5. Survey mode(s): Responses to survey questions were entered directly into computers by respondents who self-completed the electronic questionnaire (rEQ) and by interviewers who completed interviews with respondents by telephone (iEQ). 

6. Timeline: Data collection for this reference period: 2023-09-15 to 2024-03-30

7. Response rate: The 2018 GSS GVP response rate was 41.9%. The 2018, 2013 GSS GVP and 2010 CSGVP response rates (41.9%, 46.0% and 55.7% respectively) are not directly comparable. 

8. Weights: When a probability sample is used, as is the case for the GSS, the principle behind estimation is that each person selected in the sample represents (in addition to himself or herself) several other persons not in the sample. For example, in a simple random sample of 2% of a population size of 1000, each person in the sample represents 50 persons in the population. The number of persons represented by a given person in the sample is usually known as the weight or weighting factor of the sampled person. WGHT_PER is the basic weighting factor for analysis at the person level, i.e., to calculate estimates of the number of persons (non-institutionalized and aged 15 or over) having one or several given characteristics. WGHT_PER should be used for all person-level estimates. For example, to estimate the number of persons who say their health is excellent, the value of WGHT_PER is summed over all records with this characteristic. In addition to the estimation weights, bootstrap weights have been created for the purpose of design-based variance estimation. A survey weight variable with a corresponding set of 500 standard bootstrap weight variables are provided with many GSS microdata files so that a full design-based approach may be taken for doing analysis with the data.

9. Data processing: 

EDITS- Edits were performed automatically and manually at various stages of processing at macro and micro levels. Data verification was carried out using consistency and flow edits. A series of checks were done to ensure the consistency of the survey data, for example, checking the respondent's reported age against the date of birth coming from the sample file. Flow edits were used to ensure respondents followed the correct path and fix off-path situations.

ERROR DETECTION AND VALIDATION: Most error detection was done through pre-determined edits programmed into the EQ system, which allows for a valid range of codes for each question and built-in edits, and automatically follows the flow of the questionnaire.

Head office performed the same checks as the EQ system as well as more specific validation of edits that are beyond the scope of automated flow and consistency edits. Records with missing or incorrect information were, in a small number of cases, completed, corrected deterministically, or imputed from other information on the questionnaire.

10. Cleaning, imputation, etc

Except in a few cases, all imputations were made using donor imputation. This method uses donor records selected through a score function to impute missing values. Recipient records (records with item or partial non-response) were matched with donor records based on shared characteristics. The donor with the highest score filled in the missing information. If multiple donors had the highest score, one was randomly selected. Mean imputation was used when donor imputation could not be used.

Imputation was carried out in 4 blocks:

- imputation of personal income and family income;
- imputation of variables related to donations;
- imputation of the formal volunteering variables; and
- imputation of the informal volunteering variables.

11. Sources of error

Non-sampling error:

Common sources of these errors are imperfect coverage and non-response. Coverage errors (or imperfect coverage) arise when there are differences between the target population and the surveyed population. Persons without good contact information represent a part of the target population that was excluded from the surveyed population. To the extent that the excluded population differs from the rest of the target population, the results may be biased. In general, since these exclusions are small, one would expect the biases introduced to be small.

Non-response could occur at several stages in this survey. Survey estimates will be adjusted (i.e. weighted) to account for non-response cases. Other types of non-sampling errors can include response errors and processing errors.

Non-response bias:

The main method used to reduce non-response bias involved a series of adjustments to the survey weights to account for nonresponse as much as possible. Information was extracted from the frame and used to model and adjust for non-response.

Coverage error:

The SGVP 2023 frame was based on the 2021 long-form Census of Population to ensure adequate coverage of groups of interest, such as population groups. The additional socio-demographic questions from the long-form content made it possible to target individuals based on their population group. Coverage was improved (over coverage and under coverage may still exist) if we compare using several linked sources. All respondents in the ten provinces were interviewed by telephone or self-completed an electronic questionnaire. Survey estimates were adjusted (weighted) to represent all persons in the target population, including those not covered by the survey frame.

12. Limitations, known biases, etc
For the 2023 SGVP, significant effort was made to minimize bias by using a well-tested questionnaire, a proven methodology, specialized interviewers and strict quality control

13. Link to documentation and any additional sources used

(a) https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP3/U1AYY0

(b) https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&SDDS=4430

# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#3`

Describe the purpose of your survey:

You are invited to participate in a research survey for an Introduction to Sociology course under the guidance of Professor James Wood.

Purpose of the Study:
This study aims to explore the evolution of musical taste throughout a person's life. We are investigating how factors like age, personal identity, and social environment shape our engagement with music, especially popular or mainstream genres. By comparing current preferences with memories of past tastes, this research seeks to uncover the sociological forces that influence how we perceive and connect with music across different life stages.

Your participation will provide valuable insights into the relationship between culture, identity, and the life course. The survey is open to anyone aged 18 and over.

Please feel free to share this survey link with friends, family, or anyone in your network who might be interested in contributing.

Describe your target population, sampling frame, sampling units, and observational units:
``
Target Population: Individuals aged 18 and over, across multiple generations in Canada.

Sampling Frame: University students, alumni networks, community organizations, and online participants reached via email, social media, and academic outreach.

Sampling Units: Individual respondents with internet access who voluntarily complete the survey.

Observational Units: Individual respondents

Sampling Strategy: A mix of stratified purposive sampling (to ensure varied age group representation) and snowball sampling (participants invited to share the survey), supplemented by convenience sampling within the university setting.

Your 5-10 question survey:
```
1. write your question here...

What is your age group?
( ) 18–24
( ) 25–34
( ) 35–44
( ) 45–54
( ) 55–64
( ) 65 and over

2. write your question here...

In a typical week, how much time do you intentionally set aside to listen to music (not as background noise)?
A. 0–30 minutes
B. 30 minutes–2 hours
C. 2–5 hours
D. 5–10 hours
E. More than 10 hours

3. write your question here...

At what life stage did music start to feel personally meaningful to you?
A. Childhood (under 12)
B. Early adolescence (13–15)
C. Late adolescence (16–19)
D. Young adulthood (20–29)
E. Adulthood (30+)
F. I’m not sure music has ever felt personally meaningful

4. write your question here...

Which of these types of music do you find yourself defending or explaining to others?
A. Music I grew up with
B. Music that’s popular now
C. Underground/indie music
D. Music from other cultures or languages
E. I don’t feel the need to defend my music taste

5. write your question here...

Rank the following influences on your music preferences from most to least important.

Options to rank:

Personal experiences
Social circles/friends
Media or streaming algorithms
Family/early exposure
Political or cultural identity

6. write your question here... (optional)

How strongly do you agree with the following statement:

"Most people eventually prefer music from their youth because it becomes tied to their identity, not just their taste."

A. Strongly agree
B. Agree
C. Neutral
D. Disagree
E. Strongly disagree

7. write your question here... (optional)

Reflecting on your own experience, how has your perception of ‘mainstream’ or ‘popular’ music changed over time?

A. I’ve grown more critical of it
B. I’ve become more open to it
C. My opinion hasn’t changed much
D. I was never interested in popular music
E. I used to reject it, but now I appreciate it

8. write your question here... (optional)

Which statement best describes your current music taste?

A. Mostly shaped by nostalgia
B. Heavily influenced by current trends
C. A mix of old and new, shaped by curiosity
D. Mostly niche or alternative
E. Eclectic and always evolving
F. Honestly, I don’t think about it much

9. write your question here... (optional)

What genre of music do you currently listen to most often?
( ) Pop
( ) Rock
( ) Hip-Hop/Rap
( ) Classical
( ) Jazz
( ) Country
( ) Electronic/Dance
( ) Other (please specify): __________

10. write your question here... (optional)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
write your answer here
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
