
# 🎵 Dataset Information
The dataset contains 79 songs from Indian music playlists with the following attributes:

- **Song name**: Title of the track
- **Album**: Album containing the song
- **Artist**: Performer(s) of the song
- **Release date**: When the song was released
- **Length**: Duration in milliseconds
- **Popularity**: Spotify popularity score (0-100)
- **Spotify URL**: Direct link to the song on Spotify

## 🔍 Key Findings
### 1. Artist Distribution
- **Total artists**: 24 unique artists
- **Most prolific artist**: Devi Sri Prasad (12 songs)
- **Other prominent artists**: Mani Sharma (9 songs), Harris Jayaraj (6 songs), Gopi Sundar (5 songs)

### 2. Popularity Analysis
- **Average popularity score**: 47.7/100
- **Most popular song**: "Inkem Inkem Inkem Kaavaale" by Gopi Sundar (64/100)
- **Popularity distribution**: Most songs cluster in the 50-60 popularity range

### 3. Temporal Trends
- **Time span**: 1999-2024 (25 years)
- **Peak release years**: 2018-2019 with multiple popular releases
- **Recent activity**: New songs added through 2023-2024

### 4. Song Length Characteristics
- **Average song length**: 4.3 minutes
- **Longest song**: "Emantaro" by Mani Sharma (6.3 minutes)
- **Shortest song**: "Aaduvari" by Mani Sharma (3.0 minutes)

### 5. Collaboration Patterns
- **Solo tracks**: Majority of songs (85%)
- **Collaborations**: Limited number of songs with featured artists (15%)

## 📈 Visualizations Created
1. **Artist Analysis**
   - Top 10 artists by number of songs
   - Top 10 artists by average popularity
   - Artist distribution treemap

2. **Popularity Analysis**
   - Distribution of popularity scores
   - Top 10 most popular songs
   - Popularity vs. song length scatter plot

3. **Temporal Analysis**
   - Songs released by year
   - Average song length by year
   - 3D visualization of length vs. popularity vs. year

4. **Text Analysis**
   - Word cloud of common words in song titles

5. **Correlation Analysis**
   - Heatmap showing relationships between numerical features

## 🛠️ Technical Implementation
### Libraries Used
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Matplotlib**: Basic plotting and visualization
- **Seaborn**: Statistical data visualization
- **Plotly**: Interactive visualizations
- **WordCloud**: Text visualization

### Key Code Features
- **Data cleaning**: Handled missing values and data type conversions
- **Feature engineering**: Created derived features like song length in minutes and release year
- **Multiple visualization types**: Bar charts, line plots, scatter plots, treemaps, word clouds
- **Interactive elements**: Hover tooltips showing song details
- **Color schemes**: Used Spotify-inspired green color palette (#1DB954, #1ED760)

## 📋 Summary Statistics

| Metric              | Value |
|---------------------|-------|
| Total songs         | 79    |
| Unique artists      | 24    |
| Unique albums       | 66    |
| Time span           | 1999-2024 |
| Average popularity  | 47.7/100 |
| Average length      | 4.3 minutes |

## 🎯 Insights for Music Industry
- **Artist dominance**: A few artists (Devi Sri Prasad, Mani Sharma) dominate the playlist
- **Consistent quality**: Popularity scores are relatively evenly distributed
- **Modern trend**: Recent years show consistent output of new music
- **Optimal length**: Most songs are in the 3-5 minute range, aligning with streaming preferences

## 🔮 Future Analysis Directions
- **Audio features analysis**: Incorporate Spotify's audio features (danceability, energy, etc.)
- **Genre classification**: Categorize songs by sub-genres within Indian music
- **Listener demographics**: Analyze how popularity correlates with regional preferences
- **Trend prediction**: Build models to predict song popularity based on features
- **Collaboration network**: Map relationships between artists through collaborations

## 📝 Conclusion
This analysis reveals a diverse Indian music playlist with strong representation from established artists like Devi Sri Prasad and Mani Sharma. The songs span 25 years of music production, with consistent output and maintained quality as evidenced by the popularity scores. The visualization approach provides both high-level overviews and detailed insights into the characteristics of this music collection.

The code is structured to be reusable for analyzing other music playlists, with modular functions for data processing, visualization, and analysis.
