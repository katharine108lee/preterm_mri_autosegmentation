# Preterm Neonate MRI Segmentation using Deep Learning

## Scripts:
- change_labels.py: script to change the labels to be sequential since non-sequential labels caused issues with training
- create_config.py: script to create config files used by run.py to initialize all parameters and hyperparameters. saves to config folder.
- create_config_test.py: script to create config files used by test.py to initialize all parameters and hyperparameters. saves to a test folder.
- dataset.py: script to define dataset class. All prepocessing is done here.
- diff.py: script to look at the difference between true and predicted labels.
- gui.py: old script for locally hosted gui
- highres_modified.py: changed convolutional layers of MONAI highres 
- old_run.py: old run.py script 
- post_test.py: script that computes all metrics for success (confusion matrices, HD, SD, DS)
- prepData.py: script outputs csv files that contain paths to T1w, T2w, structure labels,
and tissue labels for a particular dataset. It marks a given percentage as train, val, and test files. This script has been replaced by two similar scripts, one tailored to ubc data and the other tailored to dhcp data. 
- prepData_V01.py: prepData script specifically for ubc V01 data
- prepData_V02.py: prepData script specifically for ubc V02 data
- prepData_dhcp.py: prepData script specifically for dhcp data
- run.py: training script
- test.py: copy of training script used for testing purposes

## Runs:
- contains hyperparameters and results for all runs
