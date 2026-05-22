# SKY-NAVIGATION-AI

A C++ and SFML-based flight routing and visualization application. The system processes a text dataset of global flight data, plots country coordinates visually onto a map, and calculates optimal flight paths between destinations—including direct routes and layovers.

## Features

- **Visual Map Rendering:** Draws countries as coordinate points on a graphical interface using **SFML**.
- **Optimal Pathfinding:** Implements **Dijkstra’s Algorithm** (and supporting graph algorithms) to find the most efficient routes between two selected countries.
- **Layover Support:** Intelligently calculates and displays multi-leg flights and layovers when direct routes aren't available.
- **File-Driven Data:** Dynamically parses flight and country data from standard text files.

## Prerequisites

Make sure you have a C++ compiler and the **SFML** library installed on your system.

- **SFML 2.x**
- **C++17** (or higher)
  
