# Reddit Story Analyzer (WIP)

A small read-only utility that analyzes narrative patterns, sentiment progression, and structural elements in public storytelling posts retrieved from selected Reddit subreddits.

This project does **not** interact with Reddit users or content in any way other than reading a limited set of public posts using the official Reddit Data API.

---

## 📌 Purpose

This application is designed for **lightweight text analysis** of user-generated stories on Reddit.  
It aims to:

- Identify common narrative patterns in long-form posts  
- Detect sentiment shifts across paragraphs  
- Categorize themes and topics  
- Analyze writing structures such as openings, conflicts, and resolutions  

This project is **for research and analytical purposes only**, and does not automate posting, commenting, voting, messaging, or any form of interaction with Redditors.

---

## 🔒 Compliance With Reddit Policies

This tool **fully complies** with Reddit’s Responsible Builder Policy:

- Uses only authenticated API access  
- Honors rate limits  
- Collects only publicly available post text, title, subreddit name, timestamp, and score  
- Does **not** store or process any sensitive or private user data  
- Does **not** collect usernames beyond what is visible in the retrieved post  
- No scraping of any kind  
- No redistribution or resale of Reddit data  
- All analysis is performed locally  
- Only small-scale data retrieval is performed (no mass harvesting)

---

## 🔧 Technical Overview

The application performs the following steps:

1. Authenticates using Reddit’s official OAuth2 API  
2. Fetches a **limited number** of public posts from story-oriented subreddits  
   (e.g., `r/TrueOffMyChest`, `r/TIFU`, `r/Confession`)  
3. Preprocesses the text for sentiment and narrative analysis  
4. Outputs metadata and analytical insights (WIP)

No data is posted back to Reddit or shared externally.

---

## 📁 Project Status

This is a **work in progress** and not yet ready for production use.  
Current focus areas:

- Safe and compliant read-only API access  
- Prototyping narrative classification models  
- Sentiment and structure analysis experiments  

---

## 📜 License

This project is provided for educational and research purposes only.  
It does not aim to replicate, redistribute, or compete with Reddit content or services.

---

## 🤝 Contact

For questions related to API usage or compliance, please refer to:

- Reddit Data API Documentation  
- Reddit Responsible Builder Policy

