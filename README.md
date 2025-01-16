# YouTube-Scraper

A Python tool that collects and analyzes YouTube video data based on user-specified genres. The scraper gathers comprehensive metadata from 500 videos per genre and saves it in a structured CSV format.

## Features

- Collects metadata from 500 videos per genre search
- Extracts detailed video information including:
  - Basic metadata (title, URL, description)
  - Channel information
  - Engagement metrics (views, comments)
  - Technical details (duration, captions)
  - Content categorization (tags, topics)
  - Geographic data (recording location)
- Automatically generates organized CSV files for easy data analysis
- User-friendly genre-based search functionality

## Data Collection

For each video, the tool extracts the following information:
- Video URL
- Title
- Description
- Channel Title
- Keyword Tags
- YouTube Video Category
- Topic Details
- Publication Date
- Video Duration
- View Count
- Comment Count
- Captions Availability
- Caption Text
- Recording Location

## Output

Results are saved in a CSV file on your local machine, with each row representing a video and columns containing the extracted information. The filename includes the genre for easy identification.

## Use Cases

- Content research and analysis
- YouTube trend analysis
- Metadata collection for specific genres
- Academic research on video content
- Content creator market research
- Video platform analytics

## Setup

1. **Clone the repository to your local machine using the following command:**:
   git clone https://github.com/your-username/your-repository-name.git
   cd your-repository-name
   
2. **Create a .env file in the root directory and add your YouTube API key**:
   api_key=YOUR_API_KEY

3. **Install the required dependencies**:
   pip install -r requirements.txt

4. **Run the project**:
   jupyter notebook
