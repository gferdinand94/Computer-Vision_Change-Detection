# Computer-Vision_Change-Detection
An implementation of the research paper "A Mamba-based Siamese Network for Remote Sensing Change Detection" by Jay N. Paranjape, Celso de Melo, and Vishal M. Patel.
- [paper](https://openaccess.thecvf.com/content/WACV2025/papers/Paranjape_A_Mamba-Based_Siamese_Network_for_Remote_Sensing_Change_Detection_WACV_2025_paper.pdf)
- [github](https://github.com/JayParanjape/M-CD)

# Datasets
The following are the publicly available datasets
- [DSIFN-CD](https://www.dropbox.com/s/1lr4m70x8jdkdr0/DSIFN-CD-256.zip?dl=0)
- [LEVIR-CD](https://www.dropbox.com/s/18fb5jo0npu5evm/LEVIR-CD256.zip?dl=0)
- [WHU-CD](https://www.dropbox.com/s/r76a00jcxp5d3hl/WHU-CD-256.zip?dl=0)
- [CDD](https://www.dropbox.com/s/ls9fq5u61k8wxwk/CDD.zip?dl=0)

### As this was a school project and with limited resources, we used truncated versions of these datasets. They can be found [here](https://drive.google.com/drive/folders/1HLgNcUADIX6XoCNQLJPDpTX_WTxkhad9).

### To run the current notebook `change_detection.ipynb`, upload the notebook to a Google Colab with a GPU runtime, then upload the desired datasets from the above [link](https://drive.google.com/drive/folders/1HLgNcUADIX6XoCNQLJPDpTX_WTxkhad9). In the notebook there is a section to comment out or define the datasets you'd like to include in training the model.

#### (A separate file that can be run directly on a computer will be added in the future)

# The following shows a few outputs of our trained model on the four datasets.

![Screenshot 2025-06-09 163542](https://github.com/user-attachments/assets/95027079-f340-4696-9b01-0aca7db05864)

![Screenshot 2025-06-09 163747](https://github.com/user-attachments/assets/cd32471e-f537-4195-9fcc-bfabbf50da68)

![Screenshot 2025-06-09 163809](https://github.com/user-attachments/assets/45309835-dcc3-48e0-9e23-484468fcfcc7)

![Screenshot 2025-06-09 163927](https://github.com/user-attachments/assets/6bc03cb4-be58-42a4-a97f-f53220e18309)

### Citation for the paper listed above:
Paranjape, Jay N. and de Melo, Celso and Patel, Vishal M. *A Mamba-Based Siamese Network for Remote Sensing Change Detection*. *Proceedings of the Winter Conference on Applications of Computer Vision (WACV)*. 1186-1196, February 2025
