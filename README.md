# CNIT-372-Final-Project-Spring-2023

#Purpose/Background
This project uses PL/SQL to answer questions regarding user data collected from Youtube. Social media uses a lot of data from users to make post suggestions, target adcvertisements, and more. The Oracle database in this repository will allow a user to analyze their own data and see what Youtube looks at to make it's platform user personalized.

# Database Instructions
Question 1:
The get_genre_views procedure does not require specific inputs other than execute. The procedure will sum up all the views for each genre and ouput it as total views in descending order.

Question 2:
For this procedure, you just need to run it in order to get a list of the average subscriber count for the 3 types of monetization status. It will output to the script output window in SQLDeveloper.

Question 3:
The get_favorite_channel function requires the userid to be inputted. The function will find the user's favorite channel by counting the videos watched and channel.

Question 4:
For this trigger, you need to first run the trigger. This makes it so that an INSERT or a DELETE would work. Next a row needs to be either created with an INSERT statement or removing an existing row with a DELETE statement. You need DBMS output turned on to see the output of the trigger.

Question 5:
The CNIT372WATCHTIME procedure requires 3 inputs. The first input is a user ID, and the other two inputs are dates. The procedure will find all the videos that user has watched in between the two given dates.

Question 6:
The CNIT372GENREHISTORY procedure requires a single input of a user ID. The procedure will count the number of videos a user has watched for each genre of video.

Question 7:
The get_returned_videos function requires userid to be inputted. The function will find user's watch history and find videos that the user watched more than 1 time.

Question 8:
For this procedure, you just need to run it in order to get the list of all channels that have a "Good" monetization status. It will output to the script output window in SQLDeveloper.

Question 9:
The get_genre_ratio procedure does not require user input other than execute. The procedure finds and outputs the like to view ratio and rounding it to 4 decimal points. The output is formatted to be in descending order.

Question 10:
The count_comments_by_genre procedure does not require user input other than execute. The procedure finds the number of comments on different types of genre. The output is formatted to output in descending order.

# Youtube Data Request Instructions 
<br />-
Navigate to https://takeout.google.com/settings/takeout and only select Youtube and Youtube Music. <br />-
Choose the desired frequency, file type and size. <br />-
Once the exporting process is complete, the data will be sent to your email. <br />-
Download your files and now you have your Youtube data.

