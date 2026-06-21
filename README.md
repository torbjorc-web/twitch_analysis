Visualize Twitch Gaming Data
This project uses Python and Matplotlib to create three visualizations from the Twitch practice dataset:

A bar graph of the featured games by viewer count.

A pie chart of League of Legends viewers' locations.

A line graph showing hourly viewer activity with a 15% error range.

Setup Guide
1. Install Python
Make sure Python 3 is installed on your computer. You can check by running:

bash
python --version
or:

bash
python3 --version
2. Install the required libraries
Install the libraries used in the project:

bash
pip install matplotlib numpy pandas seaborn
If you are using a virtual environment, activate it first before installing the packages.

3. Download the project files
Make sure the following files are in the same folder:

script.py

README.md

The Twitch practice dataset CSV files, if needed for your setup

4. Run the script
From the project folder, run:

bash
python script.py
or:

bash
python3 script.py
5. View the charts
The script will open three separate Matplotlib windows showing:

Featured Games bar chart

League of Legends Viewers' Whereabouts pie chart

Time Series Analysis line graph

Files
script.py: Main plotting script.

README.md: Project overview and setup instructions.

Project Summary
The project demonstrates how to use Matplotlib to create bar, pie, and line charts for Twitch streaming data. It highlights the most-watched games, where viewers are located, and how viewer counts change over time.# twitch_analysis
