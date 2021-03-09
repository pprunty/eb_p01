# eb_p01

## Prerequisites

* [Python](http://www.python.org)
* [Boost](http://www.boost.org)
* [Faber](https://stefanseefeld.github.io/faber)

## Build

Run

```
faber
```
to build the library.

## Test

Run

```c++
/**
 * \brief Class to store entire genome
 */
class Genome
{
public:
Genome(int n); 			        //!< Constructor for Gaussian_RNs

private:
int N_; 						//!< Number of random numbers to generate
std::vector<char> data_; 		//!< Vector to store generated numbers
};
```
```groovy
public class Demo {
    public static void main(String args[]) {
        System.out.println("Hello World");
    }
}
```


to run the tests.

## Build docs

Run

```
faber doc.html
```
to build the documentation.
