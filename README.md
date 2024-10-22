# GitHub User and Repository Data from Melbourne

## Overview
This project scrapes data from GitHub to gather information about users located in Melbourne with over 100 followers, as well as their public repositories.

## Bullet Points
- Scraped user and repository data using the GitHub API for users in Melbourne with over 100 followers.
- Surprising finding: Many repositories in Melbourne have more stars and watchers than expected.
- Developers should focus on creating highly visible, open-source projects to gain more followers.

## How I Scraped the Data
I used Python and the PyGithub library to interact with the GitHub API. The data was extracted and stored in two CSV files:
- `users.csv`: Contains user information.
- `repositories.csv`: Contains details about the users' public repositories.

## Interesting Finding
A majority of Melbourne developers contribute significantly to open-source projects, showcasing a vibrant local tech community.

## Recommendation
Contributing to open-source projects boosts visibility and increases followers. Developers in Melbourne are encouraged to engage in collaborative projects to enhance their GitHub presence.

## Files Included
- `fetch_users.py`: Script to fetch user data.
- `fetch_repositories.py`: Script to fetch repository data for the users.
- `users.csv`: Contains user data.
- `repositories.csv`: Contains repository data.
