# Spotify-End-To-End-Data-Engineering-Pro

-Implement Complete Data Pipeline Data Engineering Project using Spotify

-Integrating with Spotify API and extracting Data

-Deploying code on AWS Lambda for Data Extraction

-Adding trigger to run the extraction automatically

-Writing transformation function

-Building automated trigger on transformation function

-Store files on S3 properly

-Building Analytics Tables on data files using Glue and Athena

### Install Packages

pip install pandas

pip install numpy

pip install spotipy


### Project Execution Flow

Extract Data from API -> Lambda Trigger (Every 1 hour) -> Run Extract Code - > Store Raw Data -> Trigger Transform Function -> Transform Data and load it - > Query using Athena.
