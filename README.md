# Enhanced-Brain-Tumor-Classification-Through-VGG16-Based-Feature-Extraction-From-MRI

Brain tumors feature among the most lethal illnesses; this ends up they may grow given the tissue of the brain
inside the skull begins to grow evolves at once and uncontrollably. It could be cancerous or benign. Malignant tumors
have the ability to propagate rapidly throughout the brain’s surrounding tissue, while benign tumors grow more
slowly. However, benign tumors have the potential to be dangerous because, as they grow, they may cause damage to
nearby brain regions. 70% of all tumors are actually benign, while 30% tend to be malignant. Pituitary tumors
are another kind of tumor that arises from brain cells in the brain’s pituitary gland growing too quickly. Thus, early
detection is essential because brain tumors are fatal.

## Dataset Description
Enhanced Brain Tumor Classification through VGG16-based feature extraction from MRI image data is the source
of the problem. It consists of two classes of MRI scans:
1. Normal: encoded as 0. There is no tumor.
2. Tumor - encoded as 1 is the tumor.
   
When abnormal cells start to form within the brain, a brain tumor happens. Tumors can be classified into two main categories: benign and malignant. Primary tumors, which originate inside the brain, and secondary tumors, also referred
to as brain metastasis tumors, are the two types of cancerous tumors.

## Model Description
   VGG16, a deep convolutional neural network, is commonly used in medical image classification for its ability to extract and learn intricate features, facilitating accurate
diagnosis through effective pattern recognition. There are
two primary stages to the machine learning method used for picture classification: training and testing. A collection
of labelled images is used to teach the model how to extract relevant features like edges, corners, and colours during
the training phase. Following their extraction, the features are mapped by the model between the features and the
associated class labels over a number of Fully Connected (FC) layers. A loss function, which serves as a gauge for
the model’s precision in class label prediction for the training set, is minimised during the training phase. The model
moves from the training phase to the testing phase in order to classify new MRI's.

The model gathers characteristics from the fresh image once more during testing, and feeds those features into the
FC layers for categorization. The anticipated class label for the new image is the process’s output. The three main parts
of the system are the FC Layers, which map features to class labels, the Feature Extraction stage, which is usually
carried out by a convolutional neural network (CNN), and the Classification stage, which predicts the class label of
the image. In practical applications, this methodical technique enables precise and effective image classification.

![Architechture](https://private-user-images.githubusercontent.com/108020150/287455923-1c3ebdef-9135-423f-a3ce-ed1894b20952.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDE1Mjk4NjQsIm5iZiI6MTcwMTUyOTU2NCwicGF0aCI6Ii8xMDgwMjAxNTAvMjg3NDU1OTIzLTFjM2ViZGVmLTkxMzUtNDIzZi1hM2NlLWVkMTg5NGIyMDk1Mi5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjAyJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIwMlQxNTA2MDRaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT02OTAxMjNmN2M4Y2Q3ZjNiZGU2MTk4ZWFjZDY5MWVlNDg3NWFjM2JjMDMwYWFhMWMzZTNkMGU4YTE4MzMxZTY2JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.Uvg_AjlHlAEnWRUCExu4W8z2IMKDVj0Q-iQZgRlLY9s)

