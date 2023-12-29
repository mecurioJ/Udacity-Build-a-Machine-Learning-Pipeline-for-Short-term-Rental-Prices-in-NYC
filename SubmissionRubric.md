## W&B Set Up
- [ ] Public W&B project nyc_airbnb
## Exploratory Data Analysis
- [ ] Obtain sample data
## Data Cleaning
- [ ] Update all parameters
- [ ] Run basic_cleaning without errors
- [ ] Create clean_data.csv in W&B
## Data Testing
- [ ] Create a “reference” tag for the latest version of the clean_sample.csv artifact
- [ ] Implement the test_row_count and the test_price_range tests in src/data_check/test_data.py
- [ ] The pipeline runs successfully
## Data Splitting
- [ ] Split data into training, validation and test sets.
- [ ] The pipeline again runs successfully
## Train the Random Forest
- [ ] Complete the src/train_random_forest/run.py script
- [ ] The pipeline again runs successfully
- [ ] Create the model_export artifact on W&B
## Optimize Hyperparameters
- [ ] Run training with different hyperparameters
## Select the Best Model
- [ ] Select the best performing model and tag it as “prod”
## Test Set Verification
- [ ] Verify test set performance is comparable to performance on the validation set (no overfitting)
## Visualize the Pipeline
- [ ] Visualize the pipeline and verify proper structure
## Release the Pipeline
- [ ] Release v1.0.0 of the pipeline in Github
## Train the Model on a New Data Sample
- [ ] Run the released pipeline on a new sample of data, with initial failure
- [ ] Add a new cleaning step in basic_cleaning
- [ ] Prepare a new release
- [ ] Run the new release successfully