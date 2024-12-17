# NeuroSAE
Sparse Auto Encoder for high dimensional neural activity analysis and interpretation.

## Data
This SAE trains on neural recordings with the shape [frames, cells] where frames collapses across trials. Data should already be preprocessed (i.e. df/f for calcium imaging data)

## Run the Code
1. To use the notebook either launch it in Colab or clone in locally as a jupyter notebook. 
2. Adjust the directory to access the neural data.
3. Run the notebook - adjust the embedding layer size as needed. 
