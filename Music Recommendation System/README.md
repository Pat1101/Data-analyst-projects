This project implements a music recommendation system using Python, providing personalized song recommendations based on user interactions and song metadata.

**Features**

Recommendation Algorithm: Includes a Python script (Recommenders.py) that implements algorithms for generating song recommendations.

**Data Sources:**

song_data.csv: Contains metadata about songs.

triplets_file.csv: Contains user-song interaction data.

Documentation: The project includes a detailed document (PRJ Music Recommendation System.docx) describing the system's design and functionality.

**Prerequisites**

To run this project, ensure you have the following installed:

Python 3.x

Required Libraries (install using pip if not already installed):

numpy

pandas

scikit-learn

File Structure

Recommenders.py: Python script containing the recommendation algorithms.

song_data.csv: Dataset with song metadata.

triplets_file.csv: Dataset with user-song interactions.

Music Recommendation System.docx: Project documentation.

**How to Run**

Install the required libraries:

pip install numpy pandas scikit-learn

Ensure the datasets (song_data.csv and triplets_file.csv) are in the correct path.

Run the Recommenders.py script to execute the recommendation algorithms.

Data Description

song_data.csv:

Contains metadata for songs, such as song title, artist, and genre.

triplets_file.csv:

Includes user interaction data with fields like user ID, song ID, and play count.

**Future Improvements**

Implement collaborative filtering and content-based filtering for improved recommendations.

Integrate real-time user interaction feedback.

Develop a user-friendly interface for interacting with the recommendation system.

**License**

This project is available for educational purposes. Please attribute the original authors when sharing or modifying the content.

