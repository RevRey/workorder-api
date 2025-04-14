# WorkOrder API Integration

## Features

- Connects to Hexagon WorkOrder API using HTTP Basic Auth
- Uses secure `.env` file for credentials
- Processes and displays work order data using `pandas`
- Fully reproducible with a clean `environment.yml`


## Project Structure
```
WorkOrder/
├── .env.example
├── .gitignore
├── environment.yml
├── README.md        
└── workorder.ipynb  

```

## Getting Started

To run this project on your machine:

1. Clone the repo
2. Create the environment
3. Add your `.env` file
4. Launch the notebook

Follow the full steps above!

##  Create the Conda Environment 

conda env create -f environment.yml

conda activate workorder-env

## Create the .env File
Create a file named .env in the project folder 
