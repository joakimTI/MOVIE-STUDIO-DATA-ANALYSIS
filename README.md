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

1. TMDB MOVIES DATASET
	- This will give insight into which genre of movies is most popular.

2. IMDB SQL DATASET
 	- This will give insight into the best performing directors and writers of the most popular movies.

3. BOM MOVIE GROSS DATASET
	- This will give insight into  which movie studio performed the best in terms of gross sales.

### 3. DATA ANALYSIS AND VISUALIZATION

##### BUSINESS INSIGHTS
1. The Top 5 movie genres by popularity are Action, Adventure, Science Fiction, Fantasy and Comedy. Allocate resources to the top genres and patner with the best studios and directors in these top genres.

![Movie Genre Popularity](https://github.com/joakimTI/MOVIE-STUDIO-DATA-ANALYSIS/blob/master/Visualization/genre_popularity.png)

2. The list below showcases a diverse goup of directors with proven success in the movie industry. Partner with these directors for better diversity in content and outreach to audience.
    1.  Anthony Russo
    2.  Joe Russo
    3.  Nick Morris
    4.  Christopher Nolan
    5.  Sukumar
    6.  Sriram Raghavan
    7.  Nadine Labaki
    8.  Nitesh Tiwari
    9.  James Erskine
    10. Putrama Tuta

![Top Directors](https://github.com/joakimTI/MOVIE-STUDIO-DATA-ANALYSIS/blob/master/Visualization/Top_directors.png)

3. Buena Vista is the top grossing studio, which speaks to its market share and ability to generate very popular movies. Buena Vista holds a significant market share of the movies industry in terms of gross sales, which illustrates its dominance. The list below shows the top 10 studios to patner with from a gross sales standpoint: 
    1.  Buena Vista
    2.  Universal
    3.  Warner Brothers
    4.  FOX
    5.  Sony
    6.  Paramount
    7.  LGF
    8.  Warner Bros. (New Line Cinema)
    9.  Lionsgate/Summit Entertainment
    10. Paramount Pictures/DreamWorks

![Studio Gross Pie](https://github.com/joakimTI/MOVIE-STUDIO-DATA-ANALYSIS/blob/master/Visualization/studio_gross_pie.png)

![Studio Gross](https://github.com/joakimTI/MOVIE-STUDIO-DATA-ANALYSIS/blob/master/Visualization/studio_gross.png)


### 4. CONCLUSION
1. The Top 5 movie genres by popularity are Action, Adventure, Science Fiction, Fantasy and Comedy. Allocate resources to the top genres and patner with the best studios and directors in these top genres.
2. The list below showcases a diverse goup of directors with proven success in the movie industry. Partner with these directors for better diversity in content and outreach to audience.
    1.  Anthony Russo
    2.  Joe Russo
    3.  Nick Morris
    4.  Christopher Nolan
    5.  Sukumar
    6.  Sriram Raghavan
    7.  Nadine Labaki
    8.  Nitesh Tiwari
    9.  James Erskine
    10. Putrama Tuta
3. Buena Vista is the top grossing studio. Buena Vista holds a significant market share of the movies in terms of gross sales, which illustrates its dominance. The list below shows the top 10 studios to patner with from a gross sales standpoint; Buena Vista, Universal, Warner Brothers, FOX, Sony, Paramount, LGF, Warner Bros. (New Line Cinema), Lionsgate/Summit, Entertainment, Paramount Pictures/DreamWorks
