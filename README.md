# Netflix Network Analysis

## Overview
This project aims to uncover the collaborative dynamics within Netflix productions by analyzing actor and actress collaboration data and clustering content into three distinct groups.

## Dataset
In this project, I used the dataset [netflix_titles.csv](https://github.com/Beh-naz/Netflix-Network-Analysis/blob/main/netflix_titles.csv). The columns of this dataset are "show_id,	type,	title,	director,	cast,	country,	date_added,	release_year,	rating,	duration, listed_in, and	description".


## Methodology
We utilized the NetworkX package to construct a weighted undirected graph (G). In this graph, nodes represent actors, and edges connect two nodes if the actors have appeared in the same movie or show. The weight of an edge corresponds to the number of shows in which the pair of actors have collaborated.

## Results
The graph displaying the clusters of collaboration is available in the uploaded files. It provides valuable insights into the collaborative relationships among actors and actresses within Netflix productions.
![Netflix network](https://github.com/Beh-naz/Netflix-Network-Analysis/assets/141075639/147c3f7e-e780-4f85-b77c-0ee6a076066e)



Feel free to explore the results and the methodology further to gain a deeper understanding of our analysis.
