# Parallel Array Sum

A Java application that compares single-threaded and multithreaded approaches to summing a large array.
The application divides the array into multiple sections and uses separate threads to process each section concurrently. The partial results are then combined to calculate the final sum.

## Technologies

* Java
* Multithreading
* Threads
* Parallel Processing

## How It Works

The application generates an array of 200 million random integers and calculates its total sum using:

* **Single thread:** processes the entire array sequentially.
* **Multiple threads:** divides the array into sections and processes them concurrently.

The execution time of both approaches is measured and displayed.

## How to Run

1. Clone the repository.
2. Open the project in a Java IDE.
3. Run the `ArrayOfThreads.java` class.
