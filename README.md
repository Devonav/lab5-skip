Skip List and Tree Set Performance Comparison
Overview
This project aims to compare the performance of Skip List and Tree Set data structures in Java. Specifically, we measure and compare their insertion and deletion times across varying sizes of datasets.

Project Structure
Main.java: Contains the implementation of the Skip List, including the insertion and deletion methods. It also includes the code to run performance tests on both the Skip List and Tree Set.
Node.java: Defines the node structure used in the Skip List.
README.md: Documentation for the project.
Requirements
Java Development Kit (JDK) 8 or higher
An IDE or text editor for writing and running Java code
Excel or a similar spreadsheet application for documenting and plotting results
Running the Code
Compile and run Main.java:

The code in Main.java will execute performance tests on both the Skip List and Tree Set for various test sizes.
It will print the time taken for insertion and deletion operations for both data structures.
Collect Results:

Run the program multiple times (at least three) to gather enough data for averaging the results.
Document Results in Excel:

Create an Excel file to record the results from multiple runs.
Calculate the average times for insertion, deletion, and total operations for both Skip List and Tree Set.
Plot the Results:

Create three plots in Excel:
Insertion Time
Deletion Time
Total Time
Each plot should compare the performance of Skip List and Tree Set across different test sizes.



Test size: 50000
======
Skip list insertion took 44 ms.
Skip list deletion took 38 ms.
Skip list actions took 82 ms.
Tree set insertion took 17 ms.
Tree set deletion took 12 ms.
Tree set actions took 29 ms.

Test size: 100000
======
Skip list insertion took 75 ms.
Skip list deletion took 72 ms.
Skip list actions took 147 ms.
Tree set insertion took 26 ms.
Tree set deletion took 28 ms.
Tree set actions took 54 ms.

...

Test size: 300000
======
Skip list insertion took 371 ms.
Skip list deletion took 421 ms.
Skip list actions took 792 ms.
Tree set insertion took 109 ms.
Tree set deletion took 157 ms.
Tree set actions took 266 ms.
