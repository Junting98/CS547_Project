# File Directory

### Data Files
uiuc-gpa-dataset.csv: original dataset
debug_data.csv: 1000-datapoint subset of the original data with extraneous features removed and GPA calculated 
working_data.csv: 10000-datapoint subset of the original data with extraneous features removed and GPA calculated 
debug_data_onehot.csv: debug_data.csv but with categorical features converted to one-hot columns
working_data_onehot.csv: working_data.csv but with categorical features converted to one-hot columns

### Code Files
Milestone 1: Notebook for preprocessing and save data into pandas. It reads in the raw csv file and calculates class GPA and create one-hot vectors for categorical data.

Milestone 2: Preliminary visualizations. Shows distributions of each feature and distribution compared to the GPA being predicted. Also performs linear regression as a baseline accuracy measure.

Milestone 3: Neural Net experiments. Demonstrates effects of different batch sizes and dropout parameters on MLP using pytorch.

Milestone 4: Powerpoint used in video summary


