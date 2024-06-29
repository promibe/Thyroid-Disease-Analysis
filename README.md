# Thyroid-Disease-Analysis

## 1. Problem Statement
Analysis and get insight on the state of Patience as regards to Thyroid Disease

## 2. Understanding More About the Dataset
* This data set contains 13 clinicopathologic features aiming to predict recurrence of well differentiated thyroid cancer. The data set was collected in duration of 15 years and each patient was followed for at least 10 years.
* Dataset Link: https://www.kaggle.com/datasets/jainaru/thyroid-disease-data

<b>Source</b>
The data was procured from thyroid disease datasets provided by the UCI Machine Learning Repository.

<b>Content</b>
The size for the file featured within this Kaggle dataset is shown below — along with a list of attributes, and their description summaries:

* Age: The age of the patient at the time of diagnosis or treatment.
<br>

* Gender: The gender of the patient (male or female).
<br>

* Smoking: Whether the patient is a smoker or not.
<br>

* Hx Smoking: Smoking history of the patient (e.g., whether they have ever smoked).
<br>

* Hx Radiotherapy: History of radiotherapy treatment for any condition.
<br>

* Thyroid Function: The status of thyroid function, possibly indicating if there are any abnormalities.
<br>

* Physical Examination: Findings from a physical examination of the patient, which may include palpation of the thyroid gland and surrounding structures.
<br>

* Adenopathy: Presence or absence of enlarged lymph nodes (adenopathy) in the neck region.
<br>

* Pathology: Specific types of thyroid cancer as determined by pathology examination of biopsy samples.
<br>

* Focality: Whether the cancer is unifocal (limited to one location) or multifocal (present in multiple locations).
<br>

* Risk: The risk category of the cancer based on various factors, such as tumor size, extent of spread, and histological type.
<br>

* T: Tumor classification based on its size and extent of invasion into nearby structures.
<br>

* N: Nodal classification indicating the involvement of lymph nodes.
<br>

* M: Metastasis classification indicating the presence or absence of distant metastases.
<br>

* Stage: The overall stage of the cancer, typically determined by combining T, N, and M classifications.
<br>

* Response: Response to treatment, indicating whether the cancer responded positively, negatively, or remained stable after treatment.
<br>

* Recurred: Indicates whether the cancer has recurred after initial treatment.

## 3 Data Exploration
The dataset was explored and the following were observed
* From the above information, we observed that almost all the columns are object datatype i.e categorical, only the Age that is numeric
* There is no null value present in any column
* The average age is 41yrs
* The min age is 15yrs
* The max age is 82 years
* From the given dataset, female patients are 312 while male patients are 71
* We can also say that 81.46% are Females, while 18.54% are Males
* from the dataset, a total number of 31 male out of 71 males patients are not smoking but 1 has smoking history while 30 doesn't and none has Radiothreapy History
* Also, from the dataset, a total number of 40 males out of 71 males patients are smoking, 29 of then doesn't has smoking history, 11 has smoking history, then 3 has Radiothreapy History ans 8 doesn't
* from the dataset, a total number of 303 female out of 312 females patients are not smoking but 15 has smoking history while 288 doesn't and 302 doesn't have Radiothreapy History while 1 has
* Also, from the dataset, a total number of 9 females out of 312 females patients are smoking, 8 of then doesn't have smoking history, 1 has smoking history, then none has Radiothreapy History .
* Then in general a total number it was observed that the male smokes more than the females even the male patients has more of the patients with smoking and radiothreapy history than that of the females.

## 4 Data Analysis and Visualization
The dataset was analysed and visualized, check the notebook for the visualizations

## 5. General Summarized insight gotten from the dataset.
1. The female patients suffer more of the Thyroid Cancer
2. The female patients has high risk of having Thyroid Cancer.
3. Also the Patients of the age 56 and above has high risk of having Thyroid Cancer.
4. We can say that majority of the patients are of 30 to 34 yrs
5. Majority of the Patients has Excellent Response to Treatment, that means the rate of recovery are very large
6. Smoking has no effect on Thyroid Cancer
7. We could say that Most of the Patients has No Lympth Adenopathy and most of their age is between 25 to 47 years old
