# WRIVA-Project-Datasets-and-Models
Datasets and Models used for artifact segmentation.

Google Drive link for Datasets, Models, and Annotations: https://drive.google.com/drive/folders/1_Ly1mvAFTeg6gQ2fiQH5AyigZ8hG34Wz?usp=drive_link

We solely created the datasets contained in the Google Drive link. The drive consists of data sets for images with artifacts, including rain, soil, and finger-in-lense. These datasets were then used to train models capable of identifying and segmenting the specific artifact that each dataset was created around. Before training the model we annotated and labeled the artifacts in each of the images contained in the dataset and converted those annotations into a COCO-JSON file using an annotation software by makesense.ai. Each model was trained using Detectron2 for instance segmentation using our custom data.

The Google Drive link contains individual folders for the rain, soil, and finger-in-lense datasets. These folders all contain the annotations and working models created for each dataset.
