# Yahoo Fantasy Basketball Stats & Roto Rank App

This Jupyter Notebook application provides tools for managing and analyzing your Yahoo Fantasy Basketball league. It leverages the `yahoo_oauth` library to access league data and generates weekly stats tables and roto rank tables.

## Description

Tired of manually compiling stats and rankings for your Yahoo Fantasy Basketball league? This application automates the process! It fetches data from your league using `yahoo_oauth` and generates easy-to-read tables for:

* **Weekly Stats:**  Detailed weekly statistics for all teams in your league.
* **Roto Rank:**  Comprehensive roto category rankings based on cumulative stats.

## Features

* **Automated Data Retrieval:**  Seamlessly retrieves data from your Yahoo Fantasy Basketball league using `yahoo_oauth`.
* **Weekly Stats Tables:**  Generates tables displaying key stats for each team in a given week (e.g., points, rebounds, assists, steals, blocks, etc.).
* **Roto Rank Tables:**  Creates roto rank tables summarizing team performance across multiple categories, allowing for quick and easy comparison.


## Installation

1. Ensure you have Jupyter Notebook installed:  If not, install it using `pip install jupyter`.
2. Install the required libraries: `pip install yahoo_oauth pandas nested-lookup`
3. Obtain Yahoo API credentials:
    * Register an application on the Yahoo Developer Network.
    * Obtain your consumer key and consumer secret.
4. Configure authentication:
    * Follow the `yahoo_oauth` documentation to set up authentication and obtain an access token.

## Usage

1. Open the Jupyter Notebook (`weeklystats_rotorank.ipynb`).
2. Update the configuration parameters:
    * Enter your league ID.
    * Specify the week number for weekly stats.
    * Customize the roto categories as needed.
3. Run the notebook cells to fetch data, generate tables, and perform analysis.


