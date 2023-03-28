# Cucumber7.xTestNGLatestPOC
Cucumber7.xTestNGLatestPOC

This repository contains a Proof of Concept (POC) for running Cucumber tests in parallel using TestNG with Cucumber 7.x. The project demonstrates how to set up and configure your test framework to execute Cucumber scenarios in parallel with TestNG.

# Prerequisites
Java 8 or higher
Maven 3.x

# Project Structure
![Screenshot 2023-03-28 at 2 17 42 PM](https://user-images.githubusercontent.com/6771652/228205682-a412dc0b-5e9d-4390-9edc-b79c0320277d.png)




# Usage
Clone the repository:
``` git clone https://github.com/naveenanimation20/Cucumber7.xTestNGLatestPOC.git ```


# Navigate to the project directory:
``` cd Cucumber7.xTestNGLatestPOC ```

# Run the tests with Maven:
``` mvn clean test ```

The tests will execute in parallel, and you can view the test results in the target/cucumber-reports directory.

# Customization
To adjust the level of parallelism, edit the testng.xml file and update the thread-count attribute to the desired number of threads:

``` <suite name="Cucumber Parallel Suite" verbose="1" parallel="tests" thread-count="5"> ```
You can also add or remove <test> elements in the testng.xml file to control the number of parallel test executions.

# Contributing
Feel free to submit issues or pull requests if you find any bugs or have suggestions for improvements.

# License
This project is licensed under the MIT License. See the LICENSE file for more information.
