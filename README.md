# Rural Land Use Classification using U-Net  

This project explores an automated workflow for multi-class rural land use classification using a U-Net-based deep learning model. The goal is to provide an alternative to traditional (and costly) field surveys by leveraging semantic segmentation on orthophoto imagery.  

## Key Features  
- **U-Net Architecture**: Implements a proven deep learning model for semantic segmentation.  
- **Multi-Class Classification**: Covers 9 land use classes in rural regions (e.g., agriculture, settlements).  
- **Dataset**: 765 orthophoto images and masks from Padasuka Village, West Java—a predominantly agricultural area.  
- **Metrics**: Evaluated using the Jaccard Index (IoU).  

## Results  
- Training set IoU: **0.8458**  
- Test set IoU: **0.46537**  

While the model shows promise, further improvements are needed to enhance generalization on unseen data.  

## Dataset  
The dataset consists of orthophoto images and corresponding masks from **Padasuka Village, West Java**, labeled with 9 land use classes. Example classes:  
- Staple crop fields  
- Settlements  
- Roads  
- Water bodies  
