#Capstone Project: Recommender System for Netflix Content
##Summary:
The Netflix library continues to grow, presenting users with a challenge to discover content that aligns with their preferences. The main goal of this project is to develop a recommender system that improves user experience by suggesting relevant movies and TV shows based on their viewing history and preferences.
After completing data processing, the dataset is now ready for the machine learning (ML) stage. Each step of the data processing is detailed with accompanying commands.

##Netflix Dataset Attributes:
show_id: A unique identifier for each Movie/TV Show in the dataset.
type: Indicates the type of content, either Movie or TV Show.
title: The name of the Movie/TV Show.
Director: The name of the Director of the Movie/TV Show.
cast: Actors involved in the Movie/TV Show.
country: Name of the countries where the Movie/TV Show is produced.
date_added: The date on which the Movie/TV Show was added to Netflix.
release_year: The original release year of the Movie/TV Show.
rating: The rating of the Movie/TV Show is based on age.
duration: Total duration of the Movie (in minutes) or TV Show (in seasons).
listed_in: Genre of the Movie/TV Show, indicating its category or theme.
description: A summary or synopsis of the Movie/TV Show.

In this project, I want to apply a machine learning algorithm(Recommender systems) to list 10 TV shows or movies ordered based on their similarity to the first choice. 
first step: Exploring data including charts frequently tables and missing data, outliers, and ...
Second step: Handling missing data, outliers, changing data type and, ...
Third step: preprocessing for ML algorithms like changing text to lower-case 
Fourth step: apply content-based recommended systems to the data because the attributes for creating the model need domain knowledge
and according to the article attributes like Description, cast, and Director are the effective attributes to recommend the Movie. 
in the first model, I have just entered the description, and in the second one I have entered the director, cast, title, list_in, and description.
  
