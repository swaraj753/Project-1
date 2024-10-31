Stockholm GitHub Users Analysis
This project uses the GitHub API to scrape data on users in Stockholm with over 100 followers and their most recent repositories, with details on their profile and repository statistics.
One surprising finding was that a majority of active users tend to favor JavaScript, yet a notable portion includes projects with diverse language profiles.
To maximize visibility, developers could benefit from creating high-quality repositories with comprehensive documentation, as these tend to have higher engagement.
Project Overview
This project collects and analyzes data from the GitHub API to identify notable developers in Stockholm. Each user’s profile includes metadata such as company, bio, and follower counts, while each repository lists metrics like language, stargazers, and watchers.

Files Included
users.csv: Lists users with fields such as login, company, and location.
repositories.csv: Contains data on the most recent repositories per user, including full_name, language, and stargazers_count.
README.md: An overview of the project and findings.
Data Collection Process
Data was collected using the GitHub API, with custom Python scripts fetching profile and repository details. Each entry in users.csv represents a Stockholm-based user with over 100 followers, while repositories.csv logs up to 500 repositories per user.

Notable Observations
Language Preferences: JavaScript was the most popular, but Python and TypeScript also had substantial representation.
High-Engagement Projects: Repositories with detailed README files and active wikis appeared to attract more stars and followers.
Recommendations
Comprehensive Documentation: Projects with strong README files and wikis tend to engage more users.
Engagement with Followers: Developers should consider engaging their followers to foster a more active community.
Consistent Updates: Regularly updated repositories appear more frequently in searches and recommendations.
