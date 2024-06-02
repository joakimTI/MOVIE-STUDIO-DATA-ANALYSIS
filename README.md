##  INSIGHTS INTO CURRENT MOVIE INDUSTRY
### Business Problem

Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

### 1. BUSINESS UNDERSTANDING
In the world of movies, content is king. My goal is to provide comprehensive analysis and visualizations for you to make the most informed decision on what content to produce. The data-driven insights I'll provide will enhance your decision-making on aspects such as audience preference, domestic and global success of different genres, preferred writers and directors.
#### Business Questions
1. Which genres of movies are the most popular?
2. Which directors and writers have had the most popular movies?
3. Which studios have the highest grossing movies?

### 2. DATA UNDERSTANDING

#### The Data

In the folder `zippedData` are movie datasets from:

* [Box Office Mojo](https://www.boxofficemojo.com/)
* [IMDB](https://www.imdb.com/)
* [Rotten Tomatoes](https://www.rottentomatoes.com/)
* [TheMovieDB](https://www.themoviedb.org/)
* [The Numbers](https://www.the-numbers.com/)

Because it was collected from various locations, the different files have different formats. Some are compressed CSV (comma-separated values) or TSV (tab-separated values) files that can be opened using spreadsheet software or `pd.read_csv`, while the data from IMDB is located in a SQLite database.

![movie data erd](https://raw.githubusercontent.com/learn-co-curriculum/dsc-phase-1-project-v2-4/master/movie_data_erd.jpeg)

1. TMDB MOVIES DATASET
	- This will give insight into which genre of movies is most popular.

2. IMDB SQL DATASET
 	- This will give insight into the best performing directors and writers of the most popular movies.

3. BOM MOVIE GROSS DATASET
	- This will give insight into  which movie studio performed the best in terms of gross sales.

### 2. DATA ANALYSIS AND VISUALIZATION

##### BUSINESS INSIGHT
1. The Top 5 movie genres by popularity are Action, Adventure, Science Fiction, Fantasy and Comedy. Allocate resources to the top genres and patner with the best studios and directors in these top genres.

![Sine Wave Plot](https://github.com/joakimTI/MOVIE-STUDIO-DATA-ANALYSIS/blob/master/Visualization/genre_popularity.png)
