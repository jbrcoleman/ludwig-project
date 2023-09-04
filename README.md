# ludwig-project
Declaritive ML examples with Ludwig

## Example of Getting Started

1. `wget https://ludwig.ai/latest/data/rotten_tomatoes.csv`
2. Create yaml file (to train) `rotten_tomatoes.csv`
3. Train: `ludwig train --config rotten_tomatoes.yaml --dataset rotten_tomatoes.csv`
4. `wget https://ludwig.ai/latest/data/rotten_tomatoes_test.csv`
5. Predict: ludwig predict --model_path results/experiment_run/model --dataset rotten_tomatoes_test.csv
6. Evaluate: ludwig evaluate --dataset path/to/data.csv --model_path /path/to/model
7. Visualize: 