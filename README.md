# Mouse Movement Classification Project
User Recognition in a Computer Application Based on Mouse Usage Patterns
This project focuses on classifying mouse movement data based on recorded coordinate sequences in the format (x, y, ∆t). Each movement sequence represents a trajectory from the starting point to the end, capturing both spatial and temporal aspects of user interactions.

The classification is performed using labeled data provided in the file "mouse_data.txt", which contains movement sequences along with the corresponding user identity. Each entry includes the name of the person, the data sample index, and the full sequence of recorded movements.

The goal is to develop a machine learning model that can predict which of the four individuals (Dushko, Stefan, Filip, or Vesna) generated a given mouse movement sequence. The test dataset, located in "mouse_prediction.txt", contains unlabeled sequences that need to be classified accordingly.

Since the dataset does not include explicit features, an essential step in the process is to engineer meaningful features that can effectively differentiate between users based on their unique movement patterns. Various classification techniques can be applied, ranging from traditional machine learning algorithms to deep learning approaches.

Once the classification is complete, the results should be submitted in a .csv file, following the provided submission format.

This project explores behavioral biometrics and movement analysis, aiming to identify users based on their distinctive interaction patterns.
