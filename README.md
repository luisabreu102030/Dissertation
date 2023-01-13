# Dissertation manuscript
## Repository containing my Dissertation manuscript.

My master’s dissertation, entitled **“Automatic detection of daily living activities in people with Parkinson’s disease using kinematic data”**, was focused on the application of <ins>deep learning algorithms</ins> in the <ins>recognition of daily activities</ins> performed by Parkinson’s disease (PD) patients through <ins>kinematic data (acceleration and angular velocity)</ins>. 

During my master’s dissertation I have also developed a deep learning algorithm capable of <ins>recognizing gait events</ins>, namely the initial foot contact (IC) and the final foot contact (FC).

My master’s dissertation was framed in [BiRDLAB +sense project](http://birdlab.dei.uminho.pt/biofeedback-devices/), which aims to develop high technological solutions capable of monitoring, assessing, and assisting Parkinson’s disease patients.

In my dissertation you will find :
- A <ins>literature review</ins> performed by me;
- A Parkinson's disease patient **data collection protocol designed and implemented** by me;
- What <ins>Data cleaning</ins> steps were applied
- How the Dataset was divided into <ins>optimization, train, validation and test dataset</ins>.

![Dataset division](/images/dataset_schema.png)

- How does the proposed model was optimized, trained, validated and finally tested against unknown data.

![model optimization/train/validation/test stages](/images/pipeline_schema.png)

- Obtained results, their discussion and future work to do

## DL model for Human Activity Recognition in PD patients <ins>Test performance</ins> results

![Confusion matrix](/images/har_confusion_matrix.png)

|Dataset|Loss|Accuracy|Precision|Recall|F1 score|
|:----:|:----:|:----:|:----:|:----:|:----:|
|Test|0.326218|0.907432|0.944849|0.944849|0.90892|





## DL model for Human Walk IC/FC detection in PD patients <ins>Test performance</ins> results

![Confusion matrix](/images/icfc_confusion_matrix.png)

|Dataset|Loss|Accuracy|Precision|Recall|F1 score|AUC|MCC
|:----:|:----:|:----:|:----:|:----:|:----:|:----:|:----:|
|Test|0.540085|0.781152|0.774337|0.93841 |0.841554|0.854381|0.538386|
