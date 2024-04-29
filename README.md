[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/234bMY4A)
C Code README Social Network Friend Suggestion System This C program implements a friend suggestion system based on an adjacency matrix representing social connections. It allows users to input connections between individuals and provides functionalities to find a user's friends and recommend new friends based on mutual connections.

Features Friend Display: Users can input their node number to see their friends within the network. Friend Recommendation: The system suggests new connections based on mutual friends, expanding the user's social network. CSV Export: The program exports the adjacency matrix to a CSV file for visualization and further analysis. Usage Input Connections: Run the program and input the connections between individuals, where '1' indicates a friendship and '0' indicates no connection. Functionality Selection: Choose from the available options:

My friends.: Displays the friends of a specified user.
Recommend me friends: Recommends new friends based on mutual connections.
Exit: Exits the program. How to Run Compile the C program: bash Copy code gcc social_network.c -o social_network Run the executable: bash Copy code ./social_network
Python Code README Social Network Graph Visualization This Python script visualizes a social network graph using NetworkX and Matplotlib. It reads an adjacency matrix from a CSV file and generates a graph representation.

Features Graph Generation: Reads an adjacency matrix from a CSV file and generates a graph. Visualization: Visualizes the generated graph using NetworkX and Matplotlib. Usage Prepare the adjacency matrix CSV file with '1' indicating a connection and '0' indicating no connection. Run the Python script: bash Copy code python graph_visualization.py Requirements Python 3.x pandas networkx matplotlib Install the required packages using:

bash Copy code pip install pandas networkx matplotlib
