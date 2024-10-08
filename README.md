# Gun Violence

## Overview

This repository offers a complete framework for analyzing gun violence patterns in Toronto from 2004 to 2024, focusing on identifying high-risk neighborhoods, temporal trends, and community impact. It includes scripts for simulating and downloading data, data cleaning, testing, and a final written analysis paper.

## File Structure

The repo is structured as:

-   `data/raw_data` contains the raw data as obtained from OpenDataToronto as well as simulated data created by scripts/00-simulate_data.R.
-   `data/analysis_data` contains the cleaned dataset that was constructed.
-   `other` contains relevant literature, details about LLM chat interactions, and sketches.
-   `paper` contains the files used to generate the paper, including the Quarto document and reference bibliography file, as well as the PDF of the paper. 
-   `scripts` contains the R scripts used to simulate, download and clean data.
-    An R project Gun_Violence.Rproj is used.
-    All R codes are styled using styler in scripts/code_style.R

## Statement on LLM usage

Some code for graph and code had assistance from ChatGPT 4.0. The prompts and outputs were documented along with the entire chat history in other/llm/usage.txt.