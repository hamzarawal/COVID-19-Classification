# COVID-19-Classification
This COVID-19 Classification competition was assigned to Deep Learning Spring 2020 class at Information Technology University, Lahore, Pakistan. The goal was to fine-tune any backbone classifier and report their results on the test data. Test data labels are hidden, so students could verify the working of their models only on the validation data provided. This competition was organized only for learning purposes and does not hold any clinical importance.

#### Dataset Details


#### Multi-label and Multi-class Classification
This is multi-label and multi-class competition where there are three classes in total (COVID, Pneumonia and Normal). An image that belongs to COVID class also belongs to Pneumonia class. So all COVID class samples are also a sub-class of Pneumonia but an image belonging to Pneumonia class does not necessarily belongs to COVID class.

#### Methodology
Students had to submit a csv file containing classification results of test data. The csv has three columns in the following order:

1. Image Name
2. COVID
3. Pneumonia
4. Normal

The submitted results were then matched with the ground truth labels and accuracy and F1 score were reported.

