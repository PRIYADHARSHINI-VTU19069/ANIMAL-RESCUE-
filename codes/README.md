# Praroz Health Care Website

This repository contains the source code for the Praroz Health Care website, including features for health checkups, animal data visualization, and more.

## Features

- **Regular Health Checkup**: Allows users to enter an animal ID, check up on the animal's health status (age, weight, symptoms), and display whether medication is urgently needed.
- **Animal Data Visualization**: Includes links to various animal-related data visualizations (day-hour data, cow data, lactation data, scatterplot data).
- **Health Dashboard**: Displays various visualizations related to animal health using data from `hour.csv`.

## Project Structure

The project contains the following key files:

### `index.html`
- The homepage of the Praroz Health Care Website. It includes links to different sections like the health checkup page and animal data visualizations.

### `health_dashboard.html`
- Displays the health dashboard with animal data visualizations.

### `animal.css`
- Contains styles for the health checkup page, animal data page, and other UI elements.

### `app.py`
- A Flask web application that serves the HTML pages and handles form submissions for health checkups. It uses the `pandas` and `matplotlib` libraries for data processing and visualizations.

### `dataset.csv`
- A CSV file containing animal-related data that is used for visualizations in the health dashboard.



