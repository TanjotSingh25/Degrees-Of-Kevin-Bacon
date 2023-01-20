# Degrees

This project is an extended Python implementation of the "Six Degrees of Kevin Bacon" game, where the goal is to find the shortest path between 2 actors using the co-acting relationship between actors. The project utilizes the IMDb dataset to build a graph of actors and their co-acting relationships.

## Usage

The main script is `degrees.py`, which can be run from the command line as such:

> <code>python degrees.py</code>

The script will then output the shortest path between the two actors, or the message "Not connected" if no path is found.

## Data

The IMDb dataset used in this project can be downloaded from [IMDb's website](https://www.imdb.com/interfaces/). Please note that the dataset is large and may take some time to download and process.

## Note

* This project is inspired by CS50's AI course 2020.

* The script runs on the latest version of python and assumes that the data is in the current working directory.

* This script is built on the assumption that the data is in the current working directory.
