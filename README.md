# Brand Reception of Mastercard in the League of Legends Community

## The Sponsorship of Mastercard to League of Legends (2018–Present)

Mastercard became the first global sponsor of League of Legends esports in September 2018 — the first time a major payment technology company had made such a comprehensive commitment to the esports industry. The multi-year agreement with Riot Games established Mastercard as the exclusive global payment services partner for all of League of Legends’ premier tournaments. The deal includes in-game promotions, co-branded cards offered by banks worldwide, and exclusive presale privileges to major events for cardholders.

The objective of this analysis is to uncover player sentiment surrounding Mastercard’s sponsorship by examining discussions and mentions of the brand within the League of Legends subreddit (r/leagueoflegends).

## Dashboard 

https://public.tableau.com/app/profile/mark.se8364/viz/Sentiment_17619065594510/MastercardSA

<img width="1000" height="666" alt="image" src="https://github.com/user-attachments/assets/3806eda4-1f5f-42b2-aabf-2a1f0aa45e6c" />

# Research Questions

1. What percentage of mentions of Mastercard in r/leagueoflegends are positive?

2. What themes and topics are commonly discussed within each sentiment tone (positive, neutral, negative)?

## Key Findings

1. Mastercard’s visibility peaks during the annual World Championship, which drives both discussion volume and emotional engagement.

2. Positive conversations are largely tied to Mastercard’s sponsorship presence during the opening ceremonies of Worlds, where fans associate the brand with excitement, performance, and production value.

3. Negative conversations revolve around tickets, presales, bots, and scalping, suggesting frustration over perceived unfair purchasing systems, even among those with Mastercard’s presale privileges.

4. A small group of frequent contributors dominates the discussions, indicating that opinion leaders play a key role in shaping the tone around Mastercard.

## Recommendations

1. Capitalize on Worlds through additional sponsorships:
    - Build on the strong sentiment around the opening ceremony by sponsoring more behind-the-scenes or fan-accessible experiences, highlighting Mastercard’s contribution to the game.

2. Improve fairness perception in ticketing experiences:
    - Increase transparency around presales and anti-bot measures, and communicate Mastercard’s role clearly to reduce misplaced frustration over ticketing issues.

# Data Collection

PRAW (Python Reddit API Wrapper) was used to collect data directly from Reddit. This library enables structured access to Reddit’s public API, allowing for the retrieval of posts, comments, authors, timestamps, and engagement metrics.

For this project, discussions were extracted from the r/leagueoflegends subreddit, focusing on posts and comment threads that mention “Mastercard”.

- Post and comment IDs
- Author usernames
- Timestamps
- Comment hierarchy (parent-child relationships)
- Upvotes
- Text content for SA and topic analysis

# Repo Structure
```
Python-Mastercard-Brand-Analysis-in-r-leagueoflegends/
├── data/              
├── cleaned_data/      
├── mastercardlol/
├── report            
├── requirements.txt
├── LICENSE
└── README.md 
```

