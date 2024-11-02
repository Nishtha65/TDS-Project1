## TDS-Project1

- Used python's library `requests`, scraped the data by first querying the GitHub API endpoint `/search/users?q=location:Shanghai followers:>200` to retrieve users in Shanghai with over 200 followers, then retrieving each user’s details from `/users/{username}` and their repositories from `/users/{username}/repos` with parameter `sort=pushed`.

- An interesting fact from the analysis is that there is a GitHub user with the username "*huggingface*," which resembles the popular machine learning company
"**Hugging Face"**. This suggests that developers who use usernames linked to well-known industry trends or brands may attract curiosity and potentially gain additional visibility or followers.

- Actionable recommendation: Developers in **Shanghai** working in specialized fields like machine learning or AI may benefit from aligning their GitHub usernames and projects with recognizable industry terms, as it seems that recognizable names may attract higher visibility among followers. Developers should maintain active profiles with frequent repository updates to improve visibility in search results.

## Usage
Run the Python script to scrape data and save it to `users.csv` and `repositories.csv`. Ensure you have a valid GitHub API token and install the `requests` library.
