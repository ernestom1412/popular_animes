# Popular Animes
Web Scraping and Pipeline Proyects from MAL

In this repository you will find the python code to extract the most popular anime from My Anime List, these anime are not the highest rated but the ones that have been seen the most.

The code begins by importing some libreries that you will need to install if you don't have.
Then you will find the get_the_info function which will scrap the info from the main page of the most popular anime, including the links for each of the anime contained there.
Next, the function get_more_info will scrap through all of the links obtain from the main page to get even more info about every anime on the list
After all of that is done, the function put_it_in will join all of your data in one single and beautiful pandas DataFrame. Finally the function popular_animes will join all the previous functions in one while also adding the posibility of getting even more animes. It also gives you a ver cool popular_anime.csv with all the info you just scraped.

You want the top 50? Easy. The top 100? Please... The top 5000 most popular animes??? Well, also easy but you need the time to let the function think and hope the people form MyAnimeList don't get suspicious about the person trying to find out which is the 5000th most popular anime 😅

This proyect was made by Ernesto Moreno for the Web Scraping and Pipeline Proyect in Ironhack
