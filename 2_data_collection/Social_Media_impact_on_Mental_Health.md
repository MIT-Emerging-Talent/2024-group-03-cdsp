For this part of project was used open dataset from 
[kaggle](https://www.kaggle.com/datasets/souvikahmed071/social-media-and-mental-health). 
This dataset was originally collected for a data science and machine learning project 
that aimed at investigating the potential correlation between the amount of time an 
individual spends on social media and the impact it has on their mental health.

##Data fields in original dataset before the data cleaning

| Field name                                                                                                       | Data type | Description                                           |
|------------------------------------------------------------------------------------------------------------------|-----------|-------------------------------------------------------|
| Timestamp                                                                                                        | object    | Date and time                                         |
| What is your age?                                                                                                | float64   | Age                                                   |                                                  |
| Gender                                                                                                           | object    | Gender identity                                       |
| Relationship Status                                                                                              | object    | Relationships                                         |
| Occupation Status                                                                                                | object    | Occupation                                            |
| What type of organizations are you affiliated with?                                                              | object    | Organization                                          |
| Do you use social media?                                                                                         | object    | Social media usage (yes/ no )                         |
| What social media platforms do you commonly use?                                                                 | object    | List of all SM that respondent use regularly          |
| What is the average time you spend on social media every day?                                                    | object    | Average time online everyday                          |
| How often do you find yourself using Social media without a specific purpose?                                    | int64     | Procrastination section of survey, score from 1  to 5 |
| How often do you get distracted by Social media when you are busy doing something?                               | int64     | Procrastination section of survey, score from 1  to 5 |
| Do you feel restless if you haven't used Social media in a while?                                                | int64     | Anxiety section of survey, score from 1 to 5          |
| On a scale of 1 to 5, how easily distracted are you?                                                             | int64     | Procrastination section of survey, score from 1  to 5 |
| On a scale of 1 to 5, how much are you bothered by worries?                                                      | int64     | Anxiety section of survey, score from 1 to 5          |
| Do you find it difficult to concentrate on things?                                                               | int64     | Procrastination section of survey, score from 1  to 5 |
| On a scale of 1-5, how often do you compare yourself to other successful people through the use of social media? | int64     | Self-estimation, score from 1 to 5                    |
| Following the previous question, how do you feel about these comparisons, generally speaking?                    | int64     | Self-estimation, score from 1 to 5                    |
| How often do you look to seek validation from features of social media?                                          | int64     | Self-estimation, score from 1 to 5                    |
| How often do you feel depressed or down?                                                                         | int64     | Depression section of survey, score from 1 to 5       |
| On a scale of 1 to 5, how frequently does your interest in daily activities fluctuate?                           | int64     | Depression section of survey, score from 1 to 5       |
| On a scale of 1 to 5, how often do you face issues regarding sleep?                                              | int64     | Depression section of survey, score from 1 to 5       |

The dataset contains 21 column and 474 rows with the answers of respondents for the survey. 

## Analysis
More detailed information and analysis in `data_analysis/social_media_impact/README.md`

