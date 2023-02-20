In this program, the calculate_profanity() function takes in a tweet and a list of racial slurs, and returns the degree of profanity for the tweet. The function converts the tweet to lowercase for case-insensitivity, and uses a regular expression to match any of the racial slurs in the tweet. It then returns the number of matches as the degree of profanity.

The analyze_tweets() function reads in the tweets from a file specified by the filename parameter, and for each tweet, it calls the calculate_profanity() function to calculate the degree of profanity. It then prints out the tweet and its degree of profanity.

To use this program, you would need to replace racial_slurs with your own list of racial slurs, and filename with the path to your file of tweets.
