# deleted-tweets-archive



## About the Project 

Datasets generated by [SalishCoast 161](https://twitter.com/SalishCoastA) and [Karma 161](https://twitter.com/KarmaOneSixOne)
using ✨[cancel-culture](https://github.com/travisbrown/cancel-culture)✨, an open source project by [Travis Brown](https://twitter.com/travisbrown) and other tools.



## Methodology

Please note that none of the content linked here or associated with this project was accessed directly from Twitter.
All data was gathered from the [Wayback Machine](https://archive.org/web/) over several months, via the following steps:

* We choose a set of seed accounts, mostly representing far-right activists associated with .....
* We use the [Wayback Machine's CDX index](https://github.com/internetarchive/wayback/blob/master/wayback-cdx-server/README.md) to list all archived tweet URLs for these accounts.
* We download these archived pages (which are a mix of HTML and JSON) from the Wayback Machine, saving the Wayback Machine's "original" version of each page, together with the Wayback Machine's digest for that page.
* We parse these pages to extract information about individual tweets and Twitter accounts.
* We identify retweets, replies, and other relationships between accounts, and use these relationships to add new accounts to the download queue.
* We repeat these steps with the updated set of accounts.

Most of this process is automated using tools from the [cancel-culture](https://github.com/travisbrown/cancel-culture) project.





Current accounts in this archive



