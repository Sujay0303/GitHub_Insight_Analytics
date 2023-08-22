# GitHub_Insight_Analytics

**GitHub Repository: GitHub Insights Analytics**

Welcome to the GitHub Insights Analytics repository, where we dive deep into the vast GitHub landscape to uncover user behaviors, detect suspicious accounts, and provide invaluable insights into collaboration dynamics. Our comprehensive codebase empowers you to explore GitHub data through sophisticated data analysis techniques and cutting-edge algorithms. 

**Schema:**

1. `hirable`: Indicates if the user is open to job opportunities.
2. `public_repos`: Number of public repositories.
3. `is_suspicious`: Flags whether an account is suspicious.
4. `updated_at`: Timestamp of the latest user information update.
5. `id`: Unique user ID allocated by GitHub.
6. `blog`: URL of the user's public blog.
7. `followers`: Number of followers.
8. `location`: Public location of the user.
9. `follower_list`: List of IDs of users who follow the user.
10. `type`: Identifies if the account is personal, organizational, or a bot.
11. `commit_list`: Details of commit operations.
    - `commit_at`: Timestamp of code submission.
    - `generate_at`: Timestamp of author committing code changes.
    - `committer_id`: ID of the committer.
    - `author_id`: ID of the author.
    - `message`: Content of the commit message.
    - `repo_name`: Name of the committed repository.
    - `repo_id`: ID of the committed repository.
    - `repo_description`: Description of the committed repository.
    - `repo_owner_id`: ID of the owner of the committed repository.
12. `bio`: Self-description provided by the user.
13. `commits`: Number of commits made by the user.
14. `company`: Working unit of the user.
15. `following_list`: List of IDs of users being followed by the user.
16. `public_gists`: Number of public gists.
17. `name`: Nickname/exhibited name of the user.
18. `created_at`: Timestamp of account creation.
19. `email`: Public email address of the user.
20. `login`: Username/registered name of the user.
21. `repo_list`: Details of repositories created or forked by the user.
    - `full_name`: Full name of the repository.
    - `id`: Repository ID allocated by GitHub.
    - `description`: Description of the repository.
    - `size`: Size of the repository.
    - `license`: License associated with the repository.
    - `stargazers_count`: Number of stars received by the repository.
    - `fork`: Indicates whether the repository is a fork.
    - `owner_id`: ID of the owner of the repository.
    - `created_at`: Timestamp of repository creation.
    - `pushed_at`: Timestamp of the last push operation to the repository.
    - `updated_at`: Timestamp of the latest change to the repository.
    - `has_wiki`: Indicates if the repository has a wiki document.
    - `open_issues`: Number of open issues in the repository.
    - `language`: Programming language used in the repository.
    - `forks_count`: Number of forks of the repository.
    - `default_branch`: Default branch of the repository.

**Description:**

Delve into the GitHub Insights Analytics repository, your gateway to unravel GitHub's intricacies. Our project aims to empower you with informed decisions and a safer, more effective GitHub platform. With comprehensive schema detailing user profiles, commits, repositories, and more, we analyze user behaviors, detect suspicious accounts, and uncover collaboration dynamics. Dive into potential analyses such as user profile diversity, activity patterns, and programming language trends. Visualize results with PowerBI and Tableau for a deeper understanding. Join us on this journey to transform GitHub into an enlightened, secure, and collaborative community.
