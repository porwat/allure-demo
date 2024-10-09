Allure Report Sample
====================

This repository contains a sample Allure results files, along with instructions on how to generate and display an Allure report.

Introduction to Allure
----------------------

[Allure](https://allurereport.org) is a flexible, lightweight multi-language test report tool that shows a clear representation of the status of automated tests. It helps in aggregating test results, visualizing them, and making test reporting more informative and easy to understand.

Allure supports multiple frameworks, making it a great option for teams looking for versatile reporting options.

Installation
------------

To get started with Allure, you can install it by following the instructions on the [official installation page](https://allurereport.org/docs).

Cloning the Repository
------------

To use the sample results from this repository, you need to clone the repository into a folder named allure-results. Allure, by default, looks for a folder named allure-results to generate reports from.

```bash
# Clone this repository into a folder named allure-results
git clone https://github.com/your-repo-url.git allure-results
```
Once cloned, the allure-results folder will contain the sample test results that Allure will use to generate the report.

Generating and Displaying the Report
------------------------------------

Once you have Allure installed, you can generate and open the Allure report from the provided sample results using the following commands:

```bash
# Generate the Allure report from the results  
allure generate -c -o allure-report  

# Open the Allure report in your default web browser  
allure open allure-report   `
```

After running the commands, Allure will generate a report and open it in your browser for you to explore the test results.