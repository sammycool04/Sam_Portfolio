# Sam_Portfolio
Example data science portfolio


# [Project 1: Healthy/Sick Faces Classifier with OpenCV and Neural Network](https://github.com/sammycool04/OpenCV-project)
This is a project that integrate convolutional neural network(CNN), OpenCV, and Flask. The purpose is to classify healthy and sich images using computer vision and neural network. The technical design is like the followings:

* start training the CNN model using healthy and sick faces image data
* run the CNN model, save it inside the JSON file, and integrate with OpenCV using a data model
* use Flask to display the index.html file, which shows user's face health condition

![](https://github.com/sammycool04/Sam_Portfolio/blob/main/images/health.jpg)


# [Project 2: Recommendation Engine Project](https://github.com/sammycool04/Recommendation_Engine_Project)
This is a project uses IBM Watson Studio dataset to create recommendation algorithm for users. There are four parts in this project

* Exploratory Data Analysis
* Rank Based Recommendations
* User-User Based Collaborative Filtering Function create_user_item_matrix: reformat the df dataframe to be shaped with users as the rows and articles as the columns.
* Use matrix factorization to make article recommendations to the users on the IBM Watson Studio platform
* Conclusion

Latent Features vs Accuracy
![](https://github.com/sammycool04/Sam_Portfolio/blob/main/images/recommend.png)

# [Project 3:Data Pipeline and Data Processing with Spark and AWS](https://github.com/sammycool04/SparkPipeline)

## Project Structure
### Read data from S3
* Song data: s3://udacity-dend/song_data
* Log data: s3://udacity-dend/log_data
The script reads song_data and load_data from S3.

### Process data using spark
Transforms them to create five different tables listed below :

## Fact Table
*songplays - records in log data associated with song plays i.e. records with page NextSong
songplay_id, start_time, user_id, level, song_id, artist_id, session_id, location, user_agent

## Dimension Tables
* users - users in the app Fields - user_id, first_name, last_name, gender, level
* songs - songs in music database Fields - song_id, title, artist_id, year, duration
* artists - artists in music database Fields - artist_id, name, location, lattitude, longitude
* time - timestamps of records in songplays broken down into specific units Fields - start_time, hour, day, week, month, year, weekday

### Load it back to S3
Writes them to partitioned parquet files in table directories on S3.


# [Project 4: NLP Health Q&A Chatbot](https://github.com/sammycool04/NLP_Chatbot)
An NLP based chatbot integrated with neural network to generate answers for some common health concerns questions.
Technologies include
* Python Tinker, Natural Language Processing, Neural Network

![](https://github.com/sammycool04/Sam_Portfolio/blob/main/images/Screen%20Shot%202020-11-27%20at%205.07.03%20PM.png)


# [Project 5: Modelpair](https://github.com/sammycool04/Modelpair)

This is a Python package that is designed to compare different machine learning model performance on a dataset. Currently it can only deal with csv file dataset in a certain format
