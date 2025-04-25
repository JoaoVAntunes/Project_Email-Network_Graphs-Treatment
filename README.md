# Email Network Analysis

## Overview
Tool for building and analyzing graphs based on email communications,
transforming sender and recipient data into a directed and weighted network.

## Features

### Graph Generation
- Builds a directed and weighted graph from email data
- Stores the graph in text format for later analysis

### Metrics and Analysis
- **Basic Metrics**: Order (number of vertices), size (number of edges), and isolated vertices
- **Centrality**: Identifies the top 20 individuals with the highest in-degree and out-degree
- **Visualization**: Organized display of metrics and results

## Project Structure
```
/
├── controller/       # Application control logic
├── models/           # Data structures and persistence
├── utils/            # Utilities and helper tools
├── data/             # Raw and processed data
├── views/            # User interface (optional)
└── main.py           # Application entry point
```

## Technologies
- Python
- Graph data structures
- Social network analysis

## How to Use

1. Run the program:
   py main.py

3. Select an option:
   - **Generate new**: Creates a new graph from the data
   - **Extract information**: Displays metrics and analysis of the graph

## Authors
Developed as an academic project for the Graph Theory course.
By:  João Vitor Antunes, Josiel Queiroz, Matheus Moreira, Mateus Alves.

Made by heart <3
