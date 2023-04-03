Coronavirus COVID-19-Detection


# Dataset

## Data Structure
- train folder (contains 6300 chest scans in **DICOM** format)
    - study
       - series
           - image
               - .dicom files
- test data   (contains 1200 chest scans in **DICOM** format)
    - study
       - series
           - image
               - .dicom files
-  sample_submission.csv
-  train_image_level.csv
     - id - unique image identifier
     - boxes - bounding boxes in easily-readable dictionary format
     - label - the correct prediction label for the provided bounding boxes
-  train_study_level.csv 
     - id - unique study identifier
     - **Negative for Pneumonia** - 1 if the study is negative for pneumonia, 0 otherwise
     - **Typical Appearance** - 1 if the study has this appearance, 0 otherwise
     - **Indeterminate Appearance**  - 1 if the study has this appearance, 0 otherwise
     - **Atypical Appearance**  - 1 if the study has this appearance, 0 otherwise 


## Data Preprocessing
## Data Visualization
# Training


