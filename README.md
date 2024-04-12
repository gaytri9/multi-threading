# multi-threading
# Methodology
This Python script demonstrates multi-threaded matrix multiplication using the multiprocessing module. The goal is to multiply 100 random matrices of size 1000x1000 with a constant matrix of the same size using varying numbers of threads (1 to 8). The script measures the execution time and CPU usage for each configuration and generates visualizations to analyze the performance.

# How to Run the Code
To run the code, simply execute the multi_threaded_matrix_multiplication.py script in a Python environment with the required dependencies installed. You can adjust the parameters such as the number of matrices, matrix size, and number of threads in the script as needed.
python multi_threaded_matrix_multiplication.py

Result Table
The table below shows the actual and expected time taken for matrix multiplication with different numbers of threads:


Result Graphs
Execution Time vs. Number of Threads

This graph illustrates the actual execution time (solid line) compared to the expected execution time (dotted line) for different numbers of threads. As expected, the execution time decreases initially with the increase in the number of threads, but then increases again after reaching a certain point.

CPU Usage vs. Number of Threads

This graph displays the CPU usage as a percentage for different numbers of threads used in matrix multiplication. The CPU usage increases with the number of threads, peaking at a certain point before potentially decreasing due to overhead and resource contention.

You can also include any additional insights or observations about the results in the README file to provide a comprehensive understanding of the experiment.
