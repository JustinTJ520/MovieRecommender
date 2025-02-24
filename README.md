# MovieRecommender
This program uses data from the small MovieLens dataset, but could be changed to accomodate different datasets.
You can either run this locally in Jupyter Notebook or run it on Google Colab using the link in the user guide. If you decide to run it locally, download the necessary files and follow the user guide, replacing Colab instructions with jupyter instructions.
1.	Extract the files in the zip folder provided to another folder on your computer that you can easily access.
2.	Navigate to https://colab.research.google.com/drive/1Gd-KgO9GHz4timuLZ2W7Zzk9KSSYSivf?usp=sharing in your chosen web browser.
3.	Press “Runtime” in the top left of the screen.
4.	Press “Run All” in the dropdown menu.
5.	Under the second cell, press the “Choose File” button.
6.	Navigate to the folder where you stored the CSV files and select all three of the files to upload.
a.	movies.csv
b.	ratings.csv
c.	tags.csv
7.	Wait for the files to finish uploading, then scroll down to the last three cells.
8.	Under the third to last cell in the input box, type in the name of the movie you are searching for.
a.	Ex. Toy Story
9.	The movie title that you are looking for will pop up under the search box. Look at the “clean_title" column and take note of the full name with the date included.
a.	Ex. Toy Story 1995
10.	Type that full name into the next input box under the second to last cell. This will cause your movie recommendations to populate under the input box.
a.	Ex. “Toy Story 1995” will populate movies such as “Antz”, “Hook”, and “Big Trouble in Little China”.
11.	Press the buttons under the last cell labeled “Grow Graph 1/2/3” to view the graphs created from the movie data that was used to create the movie recommendation software.
a.	Graph 1: Distribution of MovieLens ratings
b.	Graph 2: Movies per Genre
c.	Graph 3: Average Rating by Genre
