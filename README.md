# Quicksort-Comparison

Operation System UPH 2017/2018 Parallel vs Singular Quicksort Comparison

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installing

A step by step series of examples that tell you how to get a development env running

Say what the step will be

```
Give the example
```

And repeat

```
until finished
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Test is done with both sequential and parallel quicksort programs to find the average time taken to finish quicksorting with a sample size of 10, 100, 1000 and 10000.

### Sequential 

| Sample Size | Test 1 Time | Test 2 Time | Test3 Time | Average Time |
|---|---|---|---|---|
| 10 | 0.004 ms | 0.003 ms | 0.002 ms | 0.003 ms|
| 100 | 0.034 ms | 0.027 ms | 0.027 ms | 0.029 ms |
| 1000 | 1.28 ms | 1.282 ms | 1.268 ms | 1,277 ms |
| 10000 | 59.045 ms | 30.715 ms | 31.518 ms | 40,426 ms |

### Parallel

| Sample Size | Test 1 Time | Test 2 Time | Test3 Time| Average Time |
|---|---|---|---|---|
| 10 | 2.553 ms | 2.501 ms | 2.545 ms | - |
| 100 | 7.99 ms | 8.449 ms | 7.755 ms | - |
| 1000 | 182.312 ms | 192.32 ms | 182.317 ms | - |
| 10000 | 7454.546 ms | 15066.25 ms | 7531.908 ms | - |

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds


## Authors

* **Johny Huang** - TIF UPH 2017

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Quicksort program taken from [markwkm quicksort repository](https://github.com/markwkm/quicksort)
* Template from [PurpleBooth Readme Template](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)
