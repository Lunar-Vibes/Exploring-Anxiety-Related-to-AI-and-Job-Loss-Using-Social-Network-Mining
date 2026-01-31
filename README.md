# Exploring Anxiety Related to AI and Job Loss Using Social Network Mining

## Project Overview

Artificial Intelligence (AI) is rapidly changing the way people work. While these technologies create new opportunities and improve efficiency, they also raise serious concerns about job security, automation, and the future of employment. Many people openly share these worries online, discussing their fears, frustrations, and personal experiences related to AI and work.

This project explores how anxiety related to AI and job loss appears in online discussions, using Reddit as the main data source. Reddit hosts many topic-focused communities where users regularly talk about careers, layoffs, automation, and uncertainty in the job market. This makes it a useful platform for understanding how people experience and react to AI-driven changes in the workplace.

The main goal of this project is to identify discussions where concerns about AI, employment insecurity, and anxiety come together, and to understand how these themes interact in real conversations.

---

## Key Objectives

- Analyze discussions related to AI, job loss, and anxiety on Reddit  
- Identify posts where multiple themes (AI, employment, anxiety) co-occur  
- Discover latent discussion themes using topic modeling (LDA)  
- Explore how different Reddit communities contribute to these themes  
- Examine temporal patterns and concept-level relationships using network analysis  

---

## Methodology Summary

The project applies multiple text mining and social network mining techniques, including:

- Text preprocessing and tokenization (unigrams and n-grams)
- Dictionary-based, rule-based text classification using three thematic pillars:
  - AI and emerging technologies  
  - Employment and economic stress  
  - Anxiety and emotional distress  
- Topic modeling using Latent Dirichlet Allocation (LDA)
- Topic assignment at the post level
- Temporal trend analysis of topic evolution
- Network-based visualizations, including:
  - Subreddit–topic networks
  - Word co-occurrence and correlation networks
  - Interactive network visualizations

---

## Main Findings

The analysis suggests that work-related anxiety expressed in online discussions is **not directly caused by AI or automation alone**. Instead, anxiety appears to be more strongly connected to **current labor market conditions**, such as mass layoffs, hiring freezes, job search difficulties, and economic uncertainty.

While AI and automation are frequently mentioned, they often function as **underlying catalysts** rather than immediate triggers of anxiety. Emotional distress is more closely associated with present market instability, with AI framed as part of a broader context of workforce disruption rather than the sole source of fear.

---

## Project Structure

The repository is organized as follows:

- **data/**  
  Contains the extracted and cleaned Reddit datasets used for analysis.

- **data_collection_code.ipynb**  
  Notebook used for collecting Reddit data via the official Reddit API, including authentication and multi-subreddit scraping.

- **source_code.ipynb**  
  Main notebook containing exploratory analysis, text preprocessing, topic modeling, and network-based analysis.

- **text_mining_project.Rmd**  
  R Markdown file used to generate the final report, including all text mining, topic modeling, and visualization steps.

- **text_mining_project.html**  
  Rendered HTML version of the final report.


- **Project.Rproj**  
  RStudio project file for reproducibility and project organization.



---

## Repository Link

🔗 **GitHub Repository:**  
https://github.com/Lunar-Vibes/Exploring-Anxiety-Related-to-AI-and-Job-Loss-Using-Social-Network-Mining

---

## Future Work

This project can be extended by:
- Applying more advanced sentiment or emotion detection methods  
- Studying long-term trends using a larger historical dataset  
- Comparing anxiety patterns across different regions or industries  
- Incorporating user-level or comment-level analysis  

---

## Authors

Shagufta Shaheen, Kacper Geisshirt, Szymon Grabowski
Master’s Student – Data Science  
University of Warsaw
