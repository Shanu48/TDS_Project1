# TDS Project 1

### [Google colab file link](https://colab.research.google.com/drive/17N9c4y--YXevZfw2mtsOUV9KesLdSgx1?usp=sharing)

## GitHub Users and Repositories Scraper

- This project utilizes Python and the GitHub API to scrape user data from developers in London with over 500 followers. The script sends GET requests to the GitHub API endpoints to fetch user details and their public repositories.
- Upon analyzing the data, we discovered that the most common surname among these developers is diverse, with multiple entries tied for first place. This finding emphasizes the global representation within the GitHub community.
- Based on our analysis, we recommend that developers actively engage with the platform by creating more repositories. Increasing the number of repositories can enhance visibility, potentially leading to more followers and networking opportunities within the developer ecosystem.

### How We Scraped the Data

1. **Using Python for API Requests**: We used the `requests` library in Python to send HTTP GET requests to the GitHub API. This allowed us to programmatically access user data based on location and follower count.
2. **Fetching Users**: The initial API call was made to search for users located in London with more than 500 followers. The response was parsed to extract relevant user information such as login ID, name, company, location, email, and more.
3. **Fetching Repositories**: For each user retrieved, we made additional API calls to fetch their public repositories. This provided insight into the users' contributions and activity levels on GitHub.
4. **Data Storage**: The scraped user and repository data were stored in CSV files (`users.csv` and `repositories.csv`) for further analysis and easy access.

### Analyzing the Data

We performed various analyses on the scraped data to uncover insights about the developer community in London. This included examining common surnames, the relationship between followers and repositories, and the programming languages used by these developers.

The insights gained from this analysis provide valuable information for developers looking to improve their presence on GitHub and understand the dynamics of the community better.
