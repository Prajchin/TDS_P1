# TDS_Toronto_P1

## Project Overview
This project analyzes GitHub data from Toronto-based users with over 100 followers to identify trends in engagement, popular programming languages, and key contributing companies. Data was collected via the GitHub API, focusing on user and repository metrics, with the aim of providing insights for developers and companies in Toronto’s GitHub community.

## Data Collection
- **Scope**: Scraped user and repository data from GitHub for Toronto-based users with more than 100 followers.
- **Source**: GitHub API.

## Key Insights
### Top Contributors by Company
Certain companies show a significant presence on GitHub, indicated by their high volume of public contributions:
- **GarnerCorp**: 2,085 repositories
- **Shopify**: 1,455 repositories
- **Quinntyne**: 1,216 repositories  

These companies demonstrate strong engagement within the open-source community.

### Languages with Highest Engagement
Niche programming languages show remarkable engagement rates, measured by stargazers and watchers per repository:
- **Cython**: Avg. 1,780 stargazers and watchers across 6 repositories
- **Forth**: Avg. 1,192 stargazers and watchers for 1 repository
- **ASP.NET**: Avg. 414 stargazers and watchers across 2 repositories
- **BrighterScript**: Avg. 313 stargazers and watchers for 1 repository
- **SAS**: Avg. 172 stargazers and watchers for 1 repository  

These findings suggest that specialized languages attract dedicated followers, possibly due to high-value applications or niche expertise.

## Recommendations
1. **Leverage High-Engagement Languages**: Developers aiming to boost visibility should consider contributing to repositories with high-engagement languages like Cython and Forth, which draw significant interest.
2. **Collaborate with Popular Companies**: Engaging with open-source projects associated with top-contributing companies, such as GarnerCorp and Shopify, can enhance developers’ profiles and networking opportunities within the community.

## File Structure
- **`users.csv`**: Details of Toronto-based GitHub users, including:
  - `login`, `name`, `company`, `location`, `bio`, `public_repos`, `followers`, `following`, `created_at`
- **`repositories.csv`**: Information on public repositories, including:
  - `full_name`, `created_at`, `stargazers_count`, `watchers_count`, `language`, `has_projects`, `has_wiki`, `license_name`

## How to Use
1. **Clone the Repository**: Download the repository files.
2. **Analyze Data**: Open `users.csv` and `repositories.csv` to explore Toronto’s GitHub landscape, assess active companies, and identify high-engagement languages.
