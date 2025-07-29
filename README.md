# BOUNTI-TR
Segmentation of 3D in-utero MRI of the fetal brain: 31 tissue labels (L/R) including transient regions of the fetal brain (subplate, periventricular white matter and proliferative zones)

# Preprocessing data for training/testing:
Please run the following commands to preprocess data before running BOUNTI-TR

# Train from scratch example: 
python ./run_bounti_tr.py ./train-imgs ./train-labels ./test-imgs ./checkpoint-folder ./results-folder 1 0 200000 

# Test trained model example: 
python ./run_bounti_tr.py ./train-imgs ./train-labels ./test-imgs ./checkpoint-folder ./results-folder 0 1 1
