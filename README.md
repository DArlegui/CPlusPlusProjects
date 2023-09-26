# A Collection Of My C++ Projects
## Flash Card Program
### Description
This is a simple C++ program that allows you to quiz yourself on U.S. states and their capitals. The program reads the state-capitol pairs from an input file (`capitols.txt`) and quizzes the user on them.

### Features
- Quiz yourself on U.S. states and their capitals.
- Randomized questions to test your knowledge.
- Keeps track of correct and incorrect answers.

### Usage
1. Compile the program using a C++ compiler.
2. Make sure you have an input file named `capitols.txt` with the state-capitol pairs (one pair per line).
3. Run the compiled program.
4. Answer the quiz questions as prompted.
5. Receive your quiz results at the end.

### Example Input File (`capitols.txt`)

### Compilation
You can compile the program using a C++ compiler. For example, using g++:

## Program 17: Graph-ADT

This program explores the Graph Abstract Data Type (ADT) using C++ classes and methods for manipulating graphs. The focus is on creating a graphical representation of an Animal Crossing world.

### Presentation

You can view the presentation here: [Program 17 Graph by Daniel Arlegui.pptx](https://github.com/DArlegui/Graph-ADT/files/10080793/Program.17.Graph.by.Daniel.Arlegui.pptx)

### Project Overview

1. **Instructions**: Using tools like PowerPoint, Keynote, or Google Slides, create a map representing a graph with at least 10 vertices. Make it clear and interesting.
   
2. **Slide Sequence**:
   - Slide 1: Map with vertices indicating roads, bridges, etc.
   - Slide 2: Graph representation (with weights) of the map.
   - Slide 3 and 4: Traversal algorithms with visual marks on copies of the map.
   - Slides 5 to at least 14: Shortest path from vertex 0 to each other vertex.
   - Last slide: Minimum Spanning Tree (MST).

### Implementation

**Part One: Traversal**
- Create a graphType object (size >= 50).
- Use `.createGraph()` with a filename to create the graph.
- Output traversal results and mark copies of the map.

**Part Two: Shortest Path**
- Create a weightedGraphType object (size >= 50).
- Use `.createWeightedGraph()` with the same filename.
- Determine shortest paths from vertex 0 to all other vertices.
- Mark the map copy to visualize these paths.

**Part Three: Minimum Spanning Tree**
- Create an msTreeType object for the MST.
- Use `.createSpanningGraph()` with the same filename.
- Output and visualize the MST on the map copy.

## Roman/Integer Converter
### Description

This C++ program is a simple Roman to Integer and Integer to Roman converter. It allows you to input Roman numerals and get their equivalent integers and vice versa.

### Usage

1. Run the program.
2. Choose one of the following options:
   - Roman to Integer Conversion.
   - Integer to Roman Conversion.
   - Quit the program.
3. Follow the on-screen instructions to perform the conversion.
4. The program will display the converted result.

### Files

- `main.cpp`: Contains the main program logic.
- `Roman.cpp`: Implements Roman to Integer and Integer to Roman conversion.
- `Roman.h`: Header file for the `Roman` class.

### Usage Example

- Converting Roman to Integer: Enter Roman characters, e.g., "IX," and get the equivalent integer value.
- Converting Integer to Roman: Enter an integer within the valid Roman numeral range (1 - 3999), e.g., "1984," and get the equivalent Roman numeral.

### Note

- The program performs basic input validation for Roman numerals and integers.
- Ensure the program is run in an environment that supports C++.

## Program 14: Searching Analysis
### Description

This C++ program performs a searching analysis using various search algorithms. It simulates searches on different-sized datasets and measures the average number of comparisons required for each search method.

### Algorithms Explored

1. Procedural Sequential Search
2. Procedural Binary Search
3. Recursive Sequential Search
4. Recursive Binary Search
5. Hashing

### Usage

1. Run the program to perform searching analysis for each algorithm.
2. The program will display the average number of comparisons for different dataset sizes.
3. Results are provided for each search method.

### Files

- `main.cpp`: Contains the main program logic and algorithm simulations.
- `Hash.cpp` and `Hash.h`: Implement the hash table for the hashing algorithm.

### Note

- The program uses random data for simulations.
- Ensure the program is run in an environment that supports C++.

## Program 6: Stock Analysis
### Description

This C++ program conducts a stock analysis by reading data from an external file, sorting it, and printing the results. The program calculates the gain for each stock and presents the data in two different ways: alphabetically by symbol and high-to-low by gain.

### Usage

1. Run the program to analyze stock data from the "stockData.txt" file.
2. The program reads and processes the data, calculating the gain for each stock.
3. It sorts the stocks by symbol and gain.
4. Results are printed to the console.

### Files

- `main.cpp`: Contains the main program logic and data processing.
- `stock.h` and `stock.cpp`: Implement the stock class and its methods.
- `stockList.h` and `stockList.cpp`: Implement the stockList class for sorting and printing.

### Note

- Ensure the "stockData.txt" file exists and contains valid data.
- This program was created as a collaborative project by Daniel Arlegui and Harpreet Basota.
