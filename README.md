# Examining the Utility and Harm of Large Language Models (LLMs) for Medical Systematic Reviews

## Medical Systematic Reviews Generated by LLMs

This repository provides the details of generating medical systematic reviews using LLMs.

### FULL LIST OF COCHRANE REVIEW TITLES AND LLM-GENERATED REVIEWS

Please refer to `cochrane_reviews_latest_by_topic_20230223.csv` for a full list of Cochrane review titles used to generate 128 reviews using LLMs.
The most recently published Cochrane reviews for each of the 37 topics were collected, and duplicates were filtered out.

![list of Cochrane topics](./Cochrane_Browse_by_Topic_20230223.png)

`llm_outputs.csv` includes all the LLM-generated reviews.
A subset of outputs have been selected for the domain expert interviews. They are available at https://llm4msr.netlify.app/

## Code for Generating Reviews

This section provides the details of generating medical systematic reviews using BioMedLM and Galactica. `get_outputs_for_cochrane_titles_galactica_biomedlm.ipynb` includes the code.
Reviews from ChatGPT were generated using the web interface.

### SETUP

Create conda environment from the environment.yml: `conda env create -f environment.yml`

Activate the conda environment: `conda activate llm4msr`

## Website Used for Interview Material

We created a website which was presented to participants during the interviews. The website includes information on high-level background of large language models and representative samples of outputs generated from LLMs.

The representative samples were used as a starting point of a discussion on the potential uses and harms of LLMs for medical systematic reviews.

The link to the website: https://llm4msr.netlify.app/
