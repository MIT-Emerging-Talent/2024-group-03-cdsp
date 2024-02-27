# Google Trends Data on ChatGPT Risks

This repository contains two datasets that provide insights into public interest and concerns regarding ChatGPT and social media, as reflected in Google search queries globally. The first dataset focuses on various negative perceptions associated with ChatGPT, while the second dataset offers a comparison between concerns related to ChatGPT and those related to social media.

## Datasets Overview

### 1. Google Trends on ChatGPT (google_trends_chatgpt_5.csv)
This dataset captures the worldwide Google search queries related to ChatGPT and associated terms like stress, threat, anxiety, fear, and dangerous from February 2019 onwards.

#### Structure
Week: The week of the year, starting from Sunday.  
chatgpt stress: (Worldwide): Search interest in "chatgpt stress" globally.  
chatgpt threat: (Worldwide): Search interest in "chatgpt threat" globally.  
chatgpt anxiety: (Worldwide): Search interest in "chatgpt anxiety" globally.  
chatgpt fear: (Worldwide): Search interest in "chatgpt fear" globally.  
chatgpt dangerous: (Worldwide): Search interest in "chatgpt dangerous" globally.  

### 2. ChatGPT vs. Social Media Concerns (google_trends_chatgpt_vs_soc_media.csv)
This dataset offers a comparative view of the global search interest in "chatgpt stress" and "chatgpt anxiety" against "social media anxiety," highlighting the public's perception and concerns over time.

#### Structure
Week: The week of the year, starting from Sunday.   
chatgpt stress: (Worldwide): Search interest in "chatgpt stress" globally.  
social media anxiety: (Worldwide): Search interest in "social media anxiety" globally.  
chatgpt anxiety: (Worldwide): Search interest in "chatgpt anxiety" globally.  


## Analysis
### Insights from the Datasets
#### ChatGPT-Related Concerns and Public Interest

![google_trends_chatgpt_5.png](img%2Fgoogle_trends_chatgpt_5.png)

The first dataset, focusing on Google Trends data related to ChatGPT and various negative perceptions (stress, threat, anxiety, fear, dangerous), illustrates a significant finding: public interest in these queries began to rise notably from the launch of ChatGPT. This uptick in search queries correlates with the increasing prominence of ChatGPT in public discourse and media coverage. The data suggests that as ChatGPT became more well-known, people started to explore not just its capabilities, but also its potential risks and impacts on mental health and safety. The growing search volume for these terms indicates a burgeoning dimension of interest and concern that could pave the way for more focused discussions, research, and analysis on the intersection of artificial intelligence and societal well-being in the future.

#### Comparative View: ChatGPT vs. Social Media

![google_trends_chatgpt_vs_soc_media.png](img%2Fgoogle_trends_chatgpt_vs_soc_media.png)

The second dataset offers a comparative perspective by juxtaposing the search interests in "chatgpt stress" and "chatgpt anxiety" with "social media anxiety." Despite the longstanding presence of social media and its well-documented impacts on mental health, the search queries related to social media anxiety have not shown a significant overall change in volume. In contrast, chatgpt-related queries, which only appeared after its introduction, have seen a noticeable increase in search volume, sometimes even surpassing that of social media anxiety. This observation is pivotal as it highlights a shift in the public's concern from traditional digital platforms to emerging AI technologies. The emergence and subsequent rise in chatgpt-related queries signal a growing awareness and apprehension about the potential psychological impacts of interacting with advanced AI, like ChatGPT.

### Implications and Future Directions

The analysis of these datasets sheds light on the evolving landscape of public interest and concern regarding digital technologies. The marked increase in ChatGPT-related queries from its inception to a point where they rival or exceed those related to social media anxiety underscores a significant shift in societal focus. This trend suggests a new dimension of interest that could influence future research, policy-making, and public discourse around AI technologies. It highlights the need for a deeper understanding of how AI, like ChatGPT, impacts mental health, privacy, security, and societal norms. As AI technologies become more integrated into daily life, monitoring and analyzing these trends will be crucial for anticipating and mitigating potential negative impacts on society.

## Source
The data was compiled using Google Trends, which provides access to a largely unfiltered sample of actual search requests made to Google. It's categorized, anonymized, and aggregated. This approach helps with understanding the broader trends over time.  

https://trends.google.com/trends/explore?date=today%205-y&q=chatgpt%20stress,chatgpt%20threat,chatgpt%20anxiety,chatgpt%20fear,chatgpt%20dangerous&hl=en

https://trends.google.com/trends/explore?date=today%205-y&q=chatgpt%20stress,social%20media%20anxiety,chatgpt%20anxiety&hl=en


## Disclaimer
Values are relative and indexed. They represent search interest relative to the highest point on the chart for the given region and time. A value of 100 is the peak popularity for the term. A value of 50 means that the term is half as popular. A score of 0 means there was not enough data for this term.