# Meli Data Analytics Case

## Getting Started

To run the project, use the following command:

``docker compose up``

## Prerequisites

For Docker to work properly, you need to create a .env file in the root folder with the following environment variables:

``JUPYTER_TOKEN=<your_token>
NB_USER=<your_user>``

## Project Structure

The project contains the following components:

### Data Ingestion Notebook 
#### Demonstrates how the data was ingested and preprocessed.

### Data Analysis Notebooks:

#### Commented Version: Contains all analysis with charts, but without executing heavy computations.

#### Full Processing Version: Runs all computations and generates charts (may be resource-intensive).

## Usage

Start the Jupyter Notebook using Docker.

Open the appropriate notebook depending on whether you want to run the full analysis or just review the commented insights.

##Notes

#The full processing notebook may require significant computational power.

#Ensure you have the required dependencies installed if running outside of Docker.
