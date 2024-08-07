# Single-cell morphometrics reveals T-box dependent patterns of epithelial tension in the Second Heart Field

### Goal: 
Understand the patterning of cardiac progenitors.The embryonic heart grows by the progressive addition of progenitor cells located on an epithelial layer known as the Dorsal pericardial wall (DPW).
T-box transcription genes (Tbx1 and Tbx5) play a key role in regulating the addition of the cells to the poles of the heart. However, the mechanisms by which the cells contribute to each pole remain unclear.
![E8 5 to E9 5 transition horizontal graph v3](https://github.com/user-attachments/assets/ac37731b-2141-4eb7-97a4-b89efddd72b4)



### To investigate this, we have:
Employed unsupervised clustering algorythms to map the cells according to their morphological features.

The data used for the analysis is stored in the Data folder. 

### Pipeline:
![figure1](https://github.com/user-attachments/assets/edccac6e-3534-4fe0-8c57-3da490ac7e71)

- Step 1: Perform Whole mount immunofluorescence on the Dorsal pericardial wall (the cardiac epithelium) using phalloidin to label the cell membranes and other proteins of interest.
- Step 2: Segment the images using [Tissue Analyser](https://github.com/baigouy/tissue_analyzer) (TA) as described by Aigouy et al.2016  .
- Step 3: Quantification of features using TA, [Force inference](https://data.mendeley.com/datasets/78ng4tmj75/4) (Kong et al. 2019) and [Dproj](https://gitlab.pasteur.fr/iah-public/DeProj) (Herbert et al. 2021).
- Step 4: Store,clean and merge the data to prepare it for machine learning algorithms.
- Step 5: Analyze the data using [joint-spatial PCA](https://github.com/SoleneS/JointSpatialPCA) (jsPCA) and further analysis.




