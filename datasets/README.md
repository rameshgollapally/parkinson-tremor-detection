# Accelerometer Dataset

This folder contains the raw accelerometer data and activity logs used for the activity recognition analysis in this project.

## File Descriptions

### 1. Accelerometer Data (`user-acc_*.csv`)
These files contain the raw time-series sensor readings collected from different subjects. 
*   **Format:** `user-acc_[ID]_[TIMESTAMP].csv`
*   **Content:** Continuous accelerometer signal data.

### 2. Activity Labels (`TrainActivities.csv`)
This file acts as the ground truth for training the model. It matches timestamps to specific activities.
*   **Key Columns:**
    *   `Activity Type`: The specific action being performed (e.g., "Sit and stand", "Shaking").
    *   `Started` / `Finished`: Timestamps for when the activity occurred.
    *   `Subject`: The ID of the person performing the activity.

### 3. Test Data (`TestActivities-20240920.csv`)
This file contains the validation or test set activity logs used to evaluate the model's performance.

## Usage Note
In the main Python notebook (`perkinson_all.ipynb`), these files are loaded using the `DATA_DIR` variable. Ensure all `.csv` files remain in this folder for the script to execute correctly.

