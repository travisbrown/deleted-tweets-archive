# deleted-tweets-archive
Deleted-Tweets-Archive

About the project




Datasets


Methodology

Please note that none of the content linked here or associated with this project was accessed directly from Twitter. All data was gathered from the Wayback Machine over several months, via the following steps:

    We choose a set of seed accounts, mostly representing far-right activists associated with 
    We use the Wayback Machine's CDX index to list all archived tweet URLs for these accounts.
    We download these archived pages (which are a mix of HTML and JSON) from the Wayback Machine, saving the Wayback Machine's "original" version of each page, together with the Wayback Machine's digest for that page.
    We parse these pages to extract information about individual tweets and Twitter accounts.
    We identify retweets, replies, and other relationships between accounts, and use these relationships to add new accounts to the download queue.
    We repeat these steps with the updated set of accounts.

Most of this process is automated using tools from the cancel-culture project.

Future plans

Current accounts in this archive



