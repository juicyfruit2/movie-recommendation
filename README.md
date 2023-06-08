## README
Welcome to the Movie Dataset project! This repository contains a movies.txt file that serves as a dataset of movie information. This README provides an overview of the dataset and instructions on how to use it.

- [Introduction](#introduction)
- [Dataset Structure](#requirements)
- [Movie Dataset](#installation)
- [Data Fields]
- [Usage](#usage)
- Docker [Install Docker](https://docs.docker.com/get-docker/)

## Introduction
The Movie Dataset is a collection of movie information stored in a text file (movies.txt). It includes details about various movies. The dataset is designed to be easy to use and can be utilized for educational purposes, data analysis, or any project requiring movie-related information.

## Dataset Structure
The movies.txt file follows a specific structure to organize the movie data. Each line in the file represents a single movie and consists of several fields separated by a delimiter (e.g., comma, tab, pipe). The fields are arranged in a predefined order to maintain consistency and facilitate data processing.

## Data Fields
The movie data in movies.txt includes the following fields:

Movie A :When Hiccup discovers Toothless isn't the only Night Fury, he must seek "The Hidden World", a secret Dragon Utopia before a hired tyrant named Grimmel finds it first.

Movie B :After the death of Superman, several new people present themselves as possible successors.

Movie C :A darkness swirls at the center of a world-renowned dance company, one that will engulf the artistic director, an ambitious young dancer, and a grieving psychotherapist. Some will succumb to the nightmare. Others will finally wake up.

Movie D :A humorous take on Sir Arthur Conan Doyle's classic mysteries featuring Sherlock Holmes and Doctor Watson.

Movie E :A 16-year-old girl and her extended family are left reeling after her calculating grandmother unveils an array of secrets on her deathbed.

Movie F :In the last moments of World War II, a young German soldier fighting for survival finds a Nazi captain's uniform. Impersonating an officer, the man -quickly takes on the monstrous identity of the perpetrators he is trying to escape from.

Movie G :The world at an end, a dying mother sends her young son on a quest to find the place that grants wishes.

Movie H :A musician helps a young singer and actress find fame, even as age and alcoholism send his own career into a downward spiral.

Movie I :Corporate analyst and single mom, Jen, tackles Christmas with a business-like approach until her uncle arrives with a handsome stranger in tow.

Movie J :Adapted from the bestselling novel by Madeleine St John, Ladies in Black is an alluring and tender-hearted comedy drama about the lives of a group of department store employees in 1959 Sydney.

Please note that each field is encoded as plain text and may contain special characters, spaces, or other formatting.

## Usage
To use the Movie Dataset in your project, follow these steps:

Clone the repository to your local machine:
git clone [repository-url]

Ensure you have Python installed on your machine. You can download the latest version of Python from the official website: https://www.python.org.

Install the required dependencies. Open a terminal or command prompt, navigate to the project directory, and run the following command: pip install -r requirements.txt

This will install the necessary packages mentioned in the requirements.txt file.

To run the Watch Next script, follow these steps:

Ensure you have the movies.txt file, which contains the movie dataset, in the same directory as the watch_next.py script.

Open a terminal or command prompt, navigate to the project directory, and run the following command: python watch_next.py

Follow the on-screen prompts to select a genre of interest. The script will randomly suggest a movie from that genre.

Repeat the process whenever you need a new movie suggestion.

## Movie Dataset
The movies.txt file serves as the movie dataset for the Watch Next script. It contains information about various movies, such as their titles, genres, directors, and release years. Each line in the file represents a single movie, with the fields separated by a delimiter.

To add or modify movies in the dataset, follow these steps:

Open the movies.txt file in a text editor.

Add a new line for each movie, following the structure of the existing lines.

Ensure that each field is separated by a delimiter, such as a comma or tab.

Save the file with the updated movie information.

Please note that modifying the dataset will impact the movie recommendations provided by the Watch Next script.

## Installing Docker
FROM pypy:latest
WORKDIR/app COPY requirements.txt . RUN pip install --no-cache-dir -r requirements.txt
COPY . . 
CMD python watch_next.py.py

Instructions to run the Dockerfile:

Save the Dockerfile in a directory. Place your app.py file and requirements.txt file in the same directory. Open a terminal and navigate to the directory where the Dockerfile is located.

Build the Docker image by running the following command: -docker build -t watch_next.py.py

Once the image is built, you can run the Docker container using the following command: docker run -p 8080:8080 watch_next.py.py

Your application should now be running inside the Docker container. You can access it by opening a web browser and navigating to http://localhost:8080 or using any other method to interact with the application.
