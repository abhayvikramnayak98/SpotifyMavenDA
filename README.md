# Spotify Wrapped: Your Personalized Music Recap

![Spotify Logo](images/spotifylogo.gif)

## Project Overview
This project demonstrates the seamless integration of Excel, Python, and Tableau to transform raw data into actionable insights and captivating visualizations, offering a complete snapshot of a user's music listening habits.

![Dashboard Screenshot](images/Dashboard%201.png)

## Project Description

The **Spotify Wrapped Dashboard** is a data-driven summary showcasing a personalized music recap for a Spotify user. This dashboard displays key metrics about music listening behavior over the year, including unique tracks, total listening time, artists, and albums. It also provides insights into monthly trends, listening habits by timeframe, and top artists, albums, and songs.

## Links

- The **first version** of this project can be found [here](https://github.com/abhayvikramnayak98/SpotifyDA). It is part of the [Maven Music Challenge](https://mavenanalytics.io/challenges/maven-music-challenge/e161353d-9967-4297-869c-505de168e610), being powered by Maven Analytics.
- The interactive **Tableau Public Dashboard** can be viewed [here](https://public.tableau.com/app/profile/abhisekh.nayak/viz/SpotifyWrappedDashboard/Dashboard1).

### Key Metrics:
- **Unique Tracks Played**: 16,527 tracks.
- **Total Listening Time**: 320.5K minutes (~5,300 hours).
- **Total Artists**: 4,113 artists explored.
- **Total Albums**: 7,947 albums.

### Listening Trends:
- **Monthly Listening Time**: A steady increase in listening time observed from February to December, peaking in November.
- **Unique Tracks Played Per Month**: Peaks in September (4.8K tracks) and August (4.5K tracks).
- **Timeframe Usage**: Most listening occurs during late night (25%) and night (26%) hours.

### Top Artists, Albums, and Songs:
- **Top Artists**: 
    - The Beatles (335.8 hours, 470 unique tracks)
    - The Killers
    - John Mayer
- **Top Albums**: 
    - The Beatles album (2,063 plays)
    - Abbey Road
- **Top Songs**: "Ode to the Mets" (1,123.8 minutes)

## Tools and Techniques

### 1. Data Cleaning and Manipulation

#### Excel:
- Used for initial cleaning, organizing raw data, and performing basic calculations (e.g., aggregating metrics like total minutes, unique tracks, etc.).
- Applied pivot tables to summarize top artists, albums, and songs.
- Conducted conditional formatting to identify trends and outliers.

#### Python:
- Used for advanced data cleaning, ensuring data integrity, and handling large datasets efficiently.
- Libraries such as `pandas` and `numpy` were employed for data wrangling (e.g., calculating monthly trends, and segmenting usage by timeframes).
- Visualization libraries like `matplotlib` and `seaborn` were utilized for creating the initial graphs.

### 2. Data Visualization

#### Tableau:
- Utilized for building the interactive and visually engaging dashboard, bringing the data story to life with charts, graphs, and clean layouts.


## Contributions

Feel free to fork the repository and submit issues or pull requests for any improvements. Contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

