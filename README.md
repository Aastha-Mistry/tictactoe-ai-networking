# TicTacToe AI Networking  

## Description  
Explore how IoT, cloud integration, and AI come together in this innovative project. This repository features the networking component of a TicTacToe game with AI, built using Raspberry Pi and Sense HAT. The project integrates cloud-based score management, data visualization, and web interfaces, showcasing skills in data handling, Python programming, and IoT systems.  

## Key Features  

- **Cloud Integration:** Online scoreboard leveraging Google Sheets API for storing and retrieving game data.  
- **Data Visualization:** Fetch and display scores on the Raspberry Pi’s RGB LED matrix or via a web interface.  
- **Web Framework:** Flask-based web server for seamless user interaction and real-time data display.  
- **Networking Analysis:** Measured network parameters using Wireshark for optimized performance.  

## Project Objectives  

1. Store and manage player scores and moves in a cloud-based database.  
2. Visualize data on an RGB LED matrix or a dynamic webpage.  
3. Evaluate and implement networking methods and cloud services for optimal integration.  
4. Develop efficient Python scripts for cloud database interaction.  
5. Set up and manage a web server for hosting the game interface.  
6. Analyze network performance between Raspberry Pi and the cloud for reliability.  
7. Enable remote gameplay via a Flask-based web application. 


**Project Structure:**

1. app.py: Python script for integrating the TicTacToe game with Google Sheets API to implement the online scoreboard.
2. main.py: Main Python script for controlling the game logic and interactions with the Sense HAT module.
3. ttsheet.json: JSON file containing configuration details for accessing the Google Sheets API.
4. webserver/: Directory containing files related to the web server setup.
5. index.html: HTML file for the webpage to display game data.
6. server.py: Python script for the web server implementation using Flask.
7. static/: Directory containing static assets (CSS, JavaScript) for the webpage.


## Usage  

1. **Clone the repository:**  
   ```bash  
   git clone https://github.com/your_username/tictactoe-networking.git 

2. **Install the required dependencies:**
pip install -r requirements.txt

Configure the ttsheet.json file with your Google Sheets API credentials.

Run the main Python script to start the TicTacToe game:
python main.py

Optionally, run the web server using Flask to display game data on a webpage:
cd webserver/
python server.py


**Contributing:**
Contributions to improve the project are welcome. You can fork the repository, make your changes, and submit a pull request for review.

**License:**
This project is licensed under the MIT License. See the LICENSE file for more details.
