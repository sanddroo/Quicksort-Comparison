# Quicksort-Comparison

Operation System UPH 2017/2018 Parallel vs Singular Quicksort Comparison

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

* GCC

### Installing

1. Download the files from the repository

2. Compile the files using "make" on the terminal in the quicksort directory

3. Execute the program using "./quicksort (sample file)" for sequential sort and "./quicksort-parallel (sample file)" for parallel sort

## Running the tests

Test is done with both sequential and parallel quicksort programs to find the average time taken to finish quicksorting with a sample size of 10, 100, 1000 and 10000.

### Sequential 

| Sample Size | Test 1 Time | Test 2 Time | Test3 Time | Average Time |
|---|---|---|---|---|
| 10 | 0.004 ms | 0.003 ms | 0.002 ms | 0.003 ms|
| 100 | 0.034 ms | 0.027 ms | 0.027 ms | 0.029 ms |
| 1000 | 1.28 ms | 1.282 ms | 1.268 ms | 1.277 ms |
| 10000 | 59.045 ms | 30.715 ms | 31.518 ms | 40.426 ms |

### Parallel

| Sample Size | Test 1 Time | Test 2 Time | Test3 Time| Average Time |
|---|---|---|---|---|
| 10 | 2.553 ms | 2.501 ms | 2.545 ms | 2.533 ms |
| 100 | 7.99 ms | 8.449 ms | 7.755 ms | 8.0647 ms |
| 1000 | 182.312 ms | 192.32 ms | 182.317 ms | 556.949 ms |
| 10000 | 7454.546 ms | 15066.25 ms | 7531.908 ms | 10017.568 ms |

## Result

### Result Comparison

| Sample Size | Sequence | Parallel |
|---|---|---|
|10| 0.003 ms | 2.533 ms |
|100| 0.029 ms | 8.0647 ms |
|1000| 1.277 ms | 556.949 ms | 
|10000| 40.426 ms | 10017.568 ms |

### Line Graph Comparison

![Quicksort Graph](https://github.com/johnyhuang/Quicksort-Comparison/blob/master/quicksort%20chart.jpg)

### Result analysis

From the result we can conclude that sequential quicksort is faster than parallel quicksort. This may however be different if the sample size for the test is much larger. According to the a paper writen by Tinku Singh and Durgesh Kumar Srivastava, if the sample size of quicksort is small, sequential quicksort is faster because of several reasons such as parallelism overhead, thread creation, time spent at synchronization, thread communication, granularity of task decomposition, etc. 

## Authors

* **Johny Huang** - TIF UPH 2017

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Quicksort program taken from [markwkm quicksort repository](https://github.com/markwkm/quicksort)
* Template from [PurpleBooth Readme Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
* [Threshold Analysis and Comparison of Sequential and Parallel Divide and Conquer Sorting Algorithms](https://pdfs.semanticscholar.org/cba9/770c4fad941fe5e501539525953a242a36f8.pdf) by Tinku Singh and Durgesh Kumar Srivastava
