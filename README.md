# Social_Media_Privacy_Analyzer
Disclaimer This tool is for educational purposes only. 
A command-line tool for analyzing privacy risks across major social media platforms, including Facebook, Instagram, YouTube, Twitter (X), Snapchat, Pinterest, Reddit, LinkedIn, Threads, and Quora. The tool uses platform-specific APIs or scraping methods to identify potential privacy concerns.

---

## Features

- Analyze privacy risks for 10+ popular social media platforms.
- Modular API integration with placeholders for user-supplied API keys.
- Easy-to-use CLI interface with options to analyze profiles or exit gracefully.
- Provides insights and recommendations for reducing privacy risks.

---

## Platforms Supported

1. Facebook
2. Instagram
3. YouTube
4. Twitter (X)
5. Snapchat
6. Pinterest
7. Reddit
8. LinkedIn
9. Threads
10. Quora

---

## Installation

### **1. Clone the Repository**
```
git clone https://github.com/your-username/social-media-privacy-analyzer.git
```
```
cd social-media-privacy-analyzer
```
## **2. Install Required Libraries**
```
pip install requests tweepy praw google-api-python-client facebook-sdk
```
## Required Libraries
requests: General-purpose HTTP requests library

tweepy: For interacting with Twitter/X API.

praw: For Reddit API integration.

google-api-python-client: For YouTube Data API.

facebook-sdk: For Facebook Graph API.

---
## Usage
```
python social_media_privacy_analyzer.py
```
### Instructions
Choose a platform from the menu.

Enter the username or profile URL when prompted.

The tool will analyze the profile and provide privacy recommendations.

Use the Exit option or press Ctrl+C to exit the program.

## Customization (for security purposes i have not given api key)
Add your API keys in the respective platform functions (e.g., analyze_twitter, analyze_facebook).

---

## Output Example:
Welcome to the Social Media Privacy Analyzer!
Select a platform to analyze:
1. Facebook
2. Instagram
3. YouTube
4. Snapchat
5. X (formerly Twitter)
6. Pinterest
7. Reddit
8. LinkedIn
9. Threads
10. Quora
11. Exit

Enter the number corresponding to the platform: 5
You selected: Twitter
Enter the profile link or username: example_user

Fetching data for Twitter profile: example_user
--- Profile Information ---
Name: Example User
Username: @example_user
Bio: Just another social media enthusiast!
Followers: 2500
Following: 300
Tweet Count: 500

--- Privacy Risk Analysis ---
- Bio contains sensitive information (e.g., email or phone number).

--- Recommendations ---
1. Review your bio for sensitive information.
2. Consider limiting public follower visibility.


