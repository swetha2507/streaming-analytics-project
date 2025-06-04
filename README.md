# StreamFlix: Analyzing What Keeps Viewers Hooked

This project explores trends in trending movie content across major streaming platforms using the TMDB API. It covers data collection, analysis, and visualizations to understand how factors like genre, runtime, and ratings relate to what content gets featured across platforms like Netflix, Disney+, and Amazon Prime.

## What This Project Covers

- Scraping movie metadata using TMDB API
- Identifying available platforms using TMDB’s watch providers
- Analyzing common genres, runtime patterns, and platform distribution
- Visualizing viewer trends using Python libraries

## Key Questions

- What genres are most common in trending titles?
- Do higher-rated movies share runtime characteristics?
- How is content distributed across streaming platforms?
- Which genres are most dominant per platform?

## Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- TMDB API for metadata and streaming availability
- Jupyter Notebook
- `.env` file for secure API key usage

## How to Run This Project

1. Clone the repository
2. Install dependencies:
pip install -r requirements.txt
3. Create a `.env` file and add your TMDB API key like this:
TMDB_API_KEY=your_tmdb_api_key_here
4. Run the notebook `main.ipynb` step-by-step

## Outputs

The notebook includes:
- A bar chart of top streaming platforms
- Top genres in trending movies
- Scatter plot of runtime vs. rating
- Box plots of runtime by genre
- Average rating by genre
- Heatmap of genre distribution by platform

## Insights

> Action and thriller are the most common genres. Movies with runtimes between 90–120 minutes tend to be rated higher. Disney+ and Netflix dominate streaming availability among popular titles.

## Project Status

This is a personal project built to strengthen my data analysis and storytelling skills. Possible next steps include:
- Analyzing TV shows in addition to movies
- Extending it with audience reviews or regional filters

## Author

Built by Swetha Srinivasan  
[LinkedIn →](https://www.linkedin.com/in/swethasrinivasan25/)

