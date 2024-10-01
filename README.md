# landslide_detection

First version (last tested 2021) in combining the different stages of the ML pipeline for my Masters research project.
First stage (found in "data_collection_notebook.ipynb") is to fetch and process the satellite data from sentinelhub that cover the Lyme Regis area in South of UK.
Second stage (found in "data_processing-exploration.ipynb") is to investigate in-depth the download satellite images - statisical analysis, visualise, normalise, stabilize (Sentinel-2 had annouce about a potential wobble in certain period of image capture)
Third stage is split into two notebooks:
    - "movement_detection.ipynb" looks at computer vision techniques that use the satellite images as a time series and predicts any movement/changes in between each capture
    - "analysing_ground_survey.ipynb" looks at the ground sensor data to compare the ground truth information with the results obtained from computer vision predictions.

References to other repos that were used in the process:
- ...
- ...
