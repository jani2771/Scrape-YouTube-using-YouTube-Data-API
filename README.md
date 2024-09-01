# Scrape-YouTube-using-YouTube-Data-API

Project Description:

This project focuses on analyzing YouTube channel and video data using Python and Google’s YouTube Data API. The aim is to extract, compare, and visualize key metrics from several Data Analyst/Data Scientist YouTube channels, providing insights into channel performance and individual video engagement.

The project is divided into two main parts:

Part 1: YouTube Channel Data Extraction and Analysis

In this part, we extract channel-level details for selected YouTube channels. The extracted data includes:

    *Channel name
    *Total number of subscribers
    *Total number of views
    *Total number of videos posted
    
Using this data, we will compare the performance of different channels, identifying which ones have the highest subscriber counts, views, and video outputs. The results will be organized into a Pandas DataFrame, followed by generating basic visualizations using Seaborn to easily compare the metrics across multiple channels.

Part 2: YouTube Video Data Extraction and Analysis

The second part focuses on analyzing video-level data from a specific YouTube channel. For each video on the channel, the following details will be extracted:

     *Video title
     *Total views
     *Total likes and dislikes
     *Total comments
     
This data will also be stored in a Pandas DataFrame, allowing us to perform further analysis on the performance of individual videos. We will create visualizations using Seaborn to highlight trends in views, likes, and engagement across the channel’s videos.

Tools and Technologies:

1)YouTube Data API: To fetch channel and video details.
2)Python: Primary programming language.
3)Google Colab: Development environment for writing and running the code.
4)Pandas: For data manipulation and analysis.
5)Seaborn: For creating visualizations to compare channel and video performance.

Project Workflow:


1)Setting Up YouTube API Access:
      *Generate a YouTube API Key.
      *Understand and explore YouTube Data API documentation to identify the relevant endpoints 
       and methods.
      *Learn how to authenticate and make API calls to access YouTube data.
      
2)Environment Setup:
      *Create a virtual environment using Anaconda.
      *Install required packages: google-api-python-client, pandas, and seaborn.
      
3)Extracting and Analyzing Channel Data:
      *Fetch channel details using the YouTube Data API.
      *Load the data into a Pandas DataFrame for analysis.
      *Visualize the channel comparison using Seaborn.
      
4)Extracting and Analyzing Video Data:
      *Fetch video details for all videos on a specific channel.
      *Load the data into a Pandas DataFrame for analysis.
      *Visualize video performance data using Seaborn.
      
By the end of this project, you will have built a Python-based tool to extract and analyze YouTube data, gaining insights into channel and video performance in the Data Analyst/Data Scientist niche.
