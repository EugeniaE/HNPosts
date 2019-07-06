# HNPosts - Exploring Hacker News Posts: when is the best time to ask questions?

This project is an example of simple data analysis with basic python libraries. I analysed public dataset of Hacker News (data up to September 26, 2016) and tried to answer the question - when is the best time during a day for a user to ask question with higher chances to get response from other users.

Hacker News is a site where users can leave their posts whicha are later voted or commended upon by other users. Very popular in technology circles and the most popular posts are seen by hundreds of thousands of users.

Dataset is was taken from here: https://www.kaggle.com/hacker-news/hacker-news-posts#HN_posts_year_to_Sep_26_2016.csv

**Dateset includes these columns:**

-**id**: The unique identifier from Hacker News for the post

-**title**: The title of the post

-**url**: The URL that the posts links to, if it the post has a URL

-**num_points**: The number of points the post acquired, calculated as the total number of upvotes minus the total number of downvotes

-**num_comments**: The number of comments that were made on the post

-**author**: The username of the person who submitted the post

-**created_at**: The date and time at which the post was submitted

# Settings: 

Python with pandas, matplotlib.

## Conclusion:

posts made at 15.00 have maximum average number of comments - 38.59! Best time to ask questions!

