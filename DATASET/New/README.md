# Instructions for Dataset

Download the FaceForensics Dataset from this [Github](https://github.com/ondyari/FaceForensics) repo by following instructions mentioned in their readme. Alternatively you can also follow the python script present in this folder:
- Python Script can be found [Here](./faceforensics_download_v4.py)

Once you've downloaded the dataset you will neeed to place it in a folder called 'DATASET'. This foler can be located where the notebooks are or can be kept in any suitable location. If so you will need to change the following variables in the [Dataset_Preparation_Notebook](../../Notebooks/Dataset_Preparation-Copy1.ipynb)

1. real_path: This will be the folder that contains the original videos from the dataset. It can be found in a folder called `original_sequences/youtube`
2. df_path: This will be the folder that contains all the deepfaked videos in the dataset. It can be found in a folder called `manipulated_sequences/Deepfakes`
3. output_path: This will be the folder to which all the processed images would be stored. You will use this as input for training your SRM and RGB models.



