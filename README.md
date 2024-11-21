# Music-Genre-Insights-Dashboard-in-Tableau

### 📽️ See the [demo video](https://drive.google.com/file/d/1ehbowFnRBV0fpjs7ouadsbOX6-59p157/view?usp=drive_link).

<p align="center">
<img height="600px" style="margin: 0 auto;" align="center" src="https://github.com/user-attachments/assets/12bd2972-a110-4b98-a82f-06432af26029"
" />
</p>

## Project Description
This project analyzes Spotify track data using Tableau, showcasing average song popularity, genre-specific acoustic features, and top artists. Interactive filters, highlights, and embedded Spotify links enhance user engagement, demonstrating Tableau's power to transform raw data into actionable music insights.

## Instructions to Create the Dashboard
Follow these steps to build the Music Genre Insights Dashboard in Tableau:

1. Download Data:
- Get the dataset from [Kaggle link](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset?resource=download).
2. Import Data into Tableau:
- Open a Tableau Workbook, connect to the CSV file, and import the data.
3. Understand the Dataset:
- Review key components: Track Identifiers, Genres, and Acoustic Dimensions.
4. Set the Dashboard Goal:
- Focus on showcasing Genre and Acoustic Popularity.
5. Apply Formatting:
- Change the workbook font to Futura for consistency.
6. Create the Charts:
- Chart 1: Average Song Popularity per Genre
    - Rows: Track Genre
    - Columns: Avg Popularity (dual axis)
    - Color: By Track Genre
    - Add: Avg Popularity to labels and Track Link to details for actions.
    - Format and title the chart.
- Chart 2: Genre Acoustic Features
    - Row: Avg Danceability
    - Column: Avg Acousticness
    - Detail: Track Genre
    - Color: By Track Genre
    - Label: Track Genre
    - Format and title the chart.
- Chart 3: Top Artists
    - Sort by popularity and add a title.
- Chart 4: Top Tracks
    - Repeat the steps for top artists.
- Chart 5: Genre Name
    - Add Track Genre in text format.
7. Assemble the Dashboard:
  - Format the title and include a Spotify logo.
  - Add a genre deep-dive section with interactive actions:
    - Filter: Select all fields.
    - Highlight: Select by Track Genre.
8. Embed Spotify Links:
  - Add a web object to display tracks using: https://<span></span>open.spotify.com/embed/track/<Track Link>
  - Add a hyperlink action to open Spotify tracks directly.

## Sources

- https://developer.spotify.com/documentation/web-api
- https://www.tableau.com/data-insights/dashboard-showcase
- https://help.tableau.com/current/pro/desktop/en-us/embed.htm
