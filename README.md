# Data analysis "The movie Database" (TMDb)

The following is an analysis of a database from The Movie Database (TMDb) which contains information on more than **10,000 films**, separated into **21 columns**:

- **id**: film identification number
- **imdb_id**: film identification number from The Movie Database (TMDb)
- **popularity**: metric used to measure the popularity of a film. (https://developers.themoviedb.org/3/getting-started/popularity)
- **budget**
- **revenue**
- **original_title**: original film name
- **cast**
- **homepage**
- **director**
- **tagline**: caption used to publicize the film
- **keywords**
- **overview**
- **runtime**
- **genres**
- **production_companies**
- **release_date**
- **vote_count**: number of votes of opinion about the film
- **vote_average**: average movie rating (from 0 to 10)
- **release_year**
- **budget_adj**: budget associated of the associated movie, in terms of 2010 dollars (accounting for inflation over time)
- **revenue_adj**: revenue associated of the associated movie, in terms of 2010 dollars (accounting for inflation over time)

**The file to analyze contain:**
- **Total Rows** = 10866
- **Total Columns** = 21

## Which answers will be answered?

The Exploratory Data Analysis is separated into **5 parts:**

- About genres
- About movies
- About popularity
- About revenue, budget and profits
- Other interesting data

Each of these items answers questions about the item you are viewing. **There are a total of 21 questions**.

- What are the most popular genres?
- Genre classification by year
- Genre classification by popularity
- What are the films with the longest running time?
- What are the films with the shortest running time?
- How has the length of films evolved over time?
- Does the length of the film affect popularity?
- What are the most popular movies?
- Does the release year affect popularity?
- Does higher revenue ensure greater popularity?
- Popularity by director and cast
- Films with higher/lower profits
- Does a higher budget ensure a higher profit?
- Relationship between budget and revenues
- Profits over the years
- Budget over the years
- Revenue over the years
- Number of films made by year
- Which actors have appeared in the most films?
- Which directors have directed the most films?
- Which production companies have directed the films?

## Used tools
- Jupyter notebooks
- Python 3 and Pandas, Numpy and matplotlib libraries
