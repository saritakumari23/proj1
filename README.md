# proj1
This project is designed to scrape data from GitHub users and repositories, specifically focusing on developers in Shanghai with over 200 followers. The data is retrieved using the GitHub API and saved into CSV files for easy analysis and reference.

## Overview

The repository contains two primary CSV files:
- **users.csv**: Information about GitHub users, including details such as username, name, company, location, bio, public repository count, followers, and account creation date.
- **repositories.csv**: Data about each user's repositories, covering repository name, creation date, stargazer and watcher counts, programming language, and project settings.

## Features

- **Data on Influential Developers**: Only users with more than 200 followers from Shanghai are included, providing a targeted dataset of influential developers in the area.
- **Detailed Repository Information**: Each user's repositories are listed with star counts, languages, and licensing information, useful for insights into their projects.
  
## CSV Files

- **`users.csv`**
  - `login`: GitHub username.
  - `name`: Display name of the user.
  - `company`: Company affiliation if provided.
  - `location`: Location of the user.
  - `email`: Contact email if publicly available.
  - `hireable`: Whether the user is open to hiring opportunities.
  - `bio`: Short bio provided by the user.
  - `public_repos`: Count of public repositories.
  - `followers`: Number of followers.
  - `following`: Number of accounts the user follows.
  - `created_at`: Account creation date.

- **`repositories.csv`**
  - `login`: GitHub username associated with the repository.
  - `full_name`: Full name of the repository (`username/repository_name`).
  - `created_at`: Repository creation date.
  - `stargazers_count`: Number of stars the repository has.
  - `watchers_count`: Number of watchers.
  - `language`: Main programming language used.
  - `has_projects`: Whether the repository has project boards enabled.
  - `has_wiki`: Whether the repository has a wiki.
  - `license_name`: License under which the repository is shared.
