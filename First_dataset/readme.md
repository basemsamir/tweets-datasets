First dataset folder structure:

1. tweet_stream.csv is a file contains more than 200000 tweets for 3 days from different users. Most tweets location is in USA.
2. tweet_stream file structure:
   Tweet Id;Date;Hour;User Name;Nickname;Bio;Tweet content;Favs;RTs;Latitude;Longitude;Country;Place (as appears on Bio);Profile picture;Followers;Following;Listed;Tweet language (ISO 639-1);Tweet Url
4. selected_users.csv is a file contains some users extracted from tweet_stream.csv.
5. selected_users file structure:
   x,freq,UserID,Username
   Note: x and UserID are the same, freq is a number of user's tweets from tweet_stream.csv file.

6. friends, followees and followers folders contains followers, followees and friends files for each selected user.

Second dataset is new_tweets.csv file. 



