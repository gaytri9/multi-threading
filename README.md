# Multi-threading
# Methodology
This Python script demonstrates multi-threaded matrix multiplication using the multiprocessing module. The goal is to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using varying numbers of threads (1 to 8). The script measures the execution time and CPU usage for each configuration and generates visualizations to analyze the performance.

# How to Run the Code
To run the code, simply execute the multi_threaded_matrix_multiplication.py script in a Python environment with the required dependencies installed. You can adjust the parameters such as the number of matrices, matrix size, and number of threads in the script as needed.

   ``` python multithreading.py ```

# Result Table
The table below shows the actual and expected time taken for matrix multiplication with different numbers of threads:
# output:-
Time taken with 1 threads: 9.97643232345581 seconds (Expected: 500 seconds)
Time taken with 2 threads: 12.022775650024414 seconds (Expected: 275 seconds)
Time taken with 3 threads: 10.7681143283844 seconds (Expected: 200 seconds)
Time taken with 4 threads: 10.693544864654541 seconds (Expected: 150 seconds)
Time taken with 5 threads: 10.500629186630249 seconds (Expected: 250 seconds)
Time taken with 6 threads: 8.620530605316162 seconds (Expected: 300 seconds)
Time taken with 7 threads: 8.12307071685791 seconds (Expected: 350 seconds)
Time taken with 8 threads: 9.09703254699707 seconds (Expected: 400 seconds)

# Result Graphs
Execution Time vs. Number of Threads
This graph illustrates the actual execution time (solid line) compared to the expected execution time (dotted line) for different numbers of threads. As expected, the execution time decreases initially with the increase in the number of threads, but then increases again after reaching a certain point.

# CPU Usage 
This graph displays the CPU usage as a percentage for different numbers of threads used in matrix multiplication. The CPU usage increases with the number of threads, peaking at a certain point before potentially decreasing due to overhead and resource contention.

