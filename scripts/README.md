This folder contains all the scripts that were used throughout the development of this project. 

`reference_list.ipynb` extracts the reference list from the given paper PDF, and looks for the reference papers as well as their metadata on PubMed and merges the references data frame with the data frame produced by scraping PubMed. 

`topic_modeling.ipynb` explores topic modeling on the title, abstract and then abstract and title together using 3 different approaches (basic, stemming, and lemmatization) to identify the most common words and phrases. It further includes a summary discussion of which methods were employed. 

`words_clouds.ipynb` visually displays the most common words and phrases identified in `topic_modeling.ipynb` through word clouds.

`keywords_search.ipynb` scrapes Pubmed's database for papers by using the most common keywords found by applying the topic modeling analysis. We defined keywords (both automatically and manually) for performing the search and compared the matches we obtained with the actual reference list.

`sports_ai_techniques.ipynb` focuses on searching for keywords in the metadata of the referenced papers in order to add the required 4 new variables to the references dataset by defining dictionaries. Later two plots were included for displaying the most common sports and AI techniques in the dataset and investigate what they were used for.