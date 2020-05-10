# COVID-19-Classification
This COVID-19 Classification competition was assigned to Deep Learning Spring 2020 class at Information Technology University, Lahore, Pakistan. The goal was to fine-tune any backbone classifier and report their results on the test data. Test data labels are hidden, so students could verify the working of their models only on the validation data provided. This competition was organized only for learning purposes and does not hold any clinical importance.

#### Dataset Details
This dataset is a sub-set of ??? open source dataset. It contains both chest X-Ray and CT-scan images. We have divided the dataset into train/validation/test sets manually. Following is the distribution:


| Class | Train | Validation | Test |
| ------------- | ------------- | ---- |
| COVID  | 200  | asd  | 29 |
| Pneumonia  | 2000  | dasd  | 2000 |
| Nomral | 4000 | asd | 400 |


Dataset can be downloaded from [here](https://drive.google.com/file/d/1eytbwaLQBv12psV8I-aMkIli9N3bf8nO/view?usp=sharing)

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

#### Multi-label and Multi-class Classification
This is multi-label and multi-class competition where there are three classes in total (COVID, Pneumonia and Normal). An image that belongs to COVID class also belongs to Pneumonia class. So all COVID class samples are also a sub-class of Pneumonia but an image belonging to Pneumonia class does not necessarily belongs to COVID class.

#### Methodology
Students had to submit a csv file containing classification results of test data. The csv has three columns in the following order:

1. Image Name
2. COVID
3. Pneumonia
4. Normal

The submitted results were then matched with the ground truth labels and accuracy and F1 score were reported.

#### Leaderboard
Results sorted by Accuracy can be found [here](https://docs.google.com/spreadsheets/d/1nPjAoDB_ZNP_JOyT1kPfSLUyLlvRynK3CpNB6a1yM9A/edit?usp=sharing)

Results sorted by F1 score can be found [here](https://docs.google.com/spreadsheets/d/1Fs2lWGIDOzYrW58Zb_HSrPPznHqJbSN0svqIuMjCDXM/edit?usp=sharing)
