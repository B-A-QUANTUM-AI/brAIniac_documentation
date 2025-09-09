# brAIniac_documentation
Repo for the documentation work of brAIniac
The proposed brAIniac AI system will automatically analyze MRI brain scans to assist in early detection and classification of brain tumors. 
The system will first detect whether a scan is healthy or shows signs of a tumor 
If a tumor is found the AI identifies its type: Glioma, Meningioma, or Pituitary Adenoma, using deep learning models trained on the BRISC 2025 dataset. 
Next, it finds the tumor’s exact size and location using image segmentation. 
Then, it assigns a risk level Low, Medium, or High based on size, location, and spread. example a report may say “Tumor detected High Priority.
Reason Large size near critical brain region.”
Then lastly it will use heatmaps to show the seriousness of the tumour and also show how it came to its final decision.
