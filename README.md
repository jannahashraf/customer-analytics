# Customer Analytics Pipeline

## Build Docker Image
docker build -t customer-analytics .

## Run Container
docker run -it --name my_container customer-analytics

## Run Pipeline
python ingest.py your_dataset.csv

## Execution Flow
ingest → preprocess → analytics → visualize → cluster

## Outputs
- data_raw.csv
- data_preprocessed.csv
- insights
- plots
- clusters

## Team Members
- Name 1
- Name 2
- Name 3