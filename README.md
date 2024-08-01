
# Worker Payment Processing

## Overview

This project involves creating Python and R scripts to facilitate the weekly payments of workers at Highridge Construction Company. The tasks include dynamically generating a list of workers, processing payment slips with conditional logic, and including error handling.

## Python Script

### Purpose

The Python script performs the following tasks:
1. Dynamically creates a list of 400 workers with random salaries and genders.
2. Generates payment slips for each worker.
3. Implements conditional logic to assign employee levels based on salary and gender.
4. Includes exception handling to manage potential errors.

### Requirements

- Python 3.x
- `pandas` library

### Setup

1. **Install the required Python package:**


2. **Save the following code in a file named `worker_payment.py`:**



### Execution

1. **Run the Python script:**
   ```bash
   python worker_payment.py
   ```

2. **Verify output:**
   - The script will generate a CSV file and zip it with the employee profile.
   - Payment slips will be printed to the console.

## R Script

### Purpose

The R script performs the following tasks:
1. Reads the worker data from a CSV file.
2. Processes the data to generate payment slips with employee levels.
3. Includes error handling to manage potential issues.

### Requirements

- R
- `utils` package (included in base R)

### Setup

1. **Save the following code in a file named `worker_payment.R`:**

  

### Execution

1. **Run the R script:**
   ```r
   Rscript worker_payment.R
   ```

2. **Verify output:**
   - The script will print the first few payment slips to the console.

---

This README provides a comprehensive guide for setting up, running, and verifying the Python and R scripts for the assignment. It ensures users understand how to execute the scripts and what outputs to expect.
