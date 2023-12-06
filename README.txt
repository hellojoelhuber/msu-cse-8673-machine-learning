# Introduction

This project was originally written on Google Colab as a final project for CSE 8673 Machine Learning.

# Instructions

Please follow these instructions to understand how to use this colab effectively.

## This means YOU!

Each section is organized by installs and imports, definitions, and then execution.

Start with Approach 2: Hierarchal Graph.

Run each code block in order: Import libraries, visualization functions, metadata calculation functions, data generation functions, then execution.

You may modify values in the execution block before running them, e.g., graph depth.

Most execution steps will run in a few seconds, depending on the number of loops you input. For example, the Hierarchal Graph execution will generate the number of graphs equal to the number you enter in the for-loop range.

## Where the Data is Stored

Data is stored in Google Drive. You should be able to see the files in Colab, or you may have viewer access at this link: https://drive.google.com/drive/folders/1-DijjYVPOJIFmlTUKeAq7owwnUfRb2K7?usp=sharing. We are not colab/Google Drive experts, so we _think_ that you will have to create your own directories in your own Google Drive to successfully run the code to generate graphs data and ML on it.

If you want to generate novel data, be sure to create a new folder to hold that data and set the execution step to correctly generate the expected data and place it in the expected output location.

## Install Dependencies

The "install dependencies" step in "Machine Learning - Graph" will take 40 or more minutes.

In our experience, you MUST install dependencies every time. As such, you may wish to run that code block first before running any other code blocks.

## IF YOU ENCOUNTER ERRORS

As of this writing (2023/11/20), running every code block in order results in the expected outputs and no errors. If you run into errors, try the following troubleshooting steps:

* You may not have a dependency installed. Run the dependency code blocks.
* You may not have run an import or definition code block. Run the import and function definition code blocks.
* You may have run code blocks out of order. Run each code block in order.
* You may not be connected to Google Drive. (Connect in Approach 2, Execution)
* You may not have the directory created inside your Google Drive. Create the directory to proceed.
* You may not have generated graphs data set (repeat Approach 2 section) and/or have a typo in your file path (check your file path for correctness).
