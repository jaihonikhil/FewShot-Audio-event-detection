

# Project Name: SEMI-SUPERVISED FEW-SHOT CLASSIFICATION USING PROTOTYPICAL NETWORKS (5 way 5 shot)

We have shown results on two kinds of datasets. D1 and D2 with 300 samples in each class.

 D1:  10 classes of UrbanSound8K dataset and 20 classes of FSD Dataset
 
 D2:  20 classes of FSD Dataset
 
 The Distribution of the training vs testing dataset is 7:3 i.e 21 random classes for training and 9 random classes for testing.
 
 Since our model also uses the unlabeled dataset in semi-supervised models, the distribution accordingly is 40% labeled and 60% unlabeled data in both Testing and Training      
 Dataset.
 
The repository contains :
1. Preprocessing Code and feature extraction which is similar for both UrbanSound8K dataset and FSD Dataset  : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/FeatureExtraction.ipynb">FeatureExtraction.ipynb</a> 
2. Google Collab with Baseline on the supervised prototypical network with results on D1 and D2. : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/Protonet_baseline.ipynb">Protonet_baseline.ipynb</a> 
3. Google Collab with semi-supervised prototypical network with soft k-means (3.1) with results on D1 and D2 : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/Protonet_Main_3_1.ipynb">Protonet_Main_3_1.ipynb</a> 
4. Google Collab with semi-supervised prototypical network with soft k-means and distractor class (3.2) with results on D1 and D2 : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/Protonet_Main_3_2.ipynb">Protonet_Main_3_2.ipynb</a> 
6. Google Collab with semi-supervised prototypical network with soft k-means and masking (3.3) with results on D1 and D2 : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/Protonet_Main_3_3.ipynb">Protonet_Main_3_3.ipynb</a> 
7.  Google Collab with semi-supervised prototypical network with soft k-means, masking and distractor class (3.4) with results on D1 and D2 : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/Protonet_Main_3_4.ipynb">Protonet_Main_3_4.ipynb</a> 
8. The report outlining our methods in detail and results : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/tree/main/ADMLReport">ADMLReport</a> 
9. Dataset D1 and D2 We provide our drive dataset for the same as the dataset size didnt allow the data to be put in drive: <a style="color:#02ccff" href="https://drive.google.com/drive/folders/1u1BTQ4W4wUeXhK4bQUrgH3b64Y9kxwj_?usp=sharing">300Data</a> 
10. Trained Models which can directly be loaded and tested upon : <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/tree/main/Models">Models</a> 
11. Dataset_classes.txt contains the list of all the classes that we are using of both the urbansound8K and FSD dataset. <a style="color:#02ccff" href="https://github.com/ee698r/ee698r-project-jaihonikhil/blob/main/Dataset_Classes.txt">Dataset_classes.txt</a> 
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

#  Code Implementation

We have already provided the preprocessed data D1 and D2 and the model checkpoints. Hence, for reproducing the results one can either run the entire google collabs of the model to train and then test or just directly load the model checkpoint and reproduce the results.

For baseline : Checkpoint Model  baselineCOMBINE.pt  for D1 and Checkpoint Model  baselineFSD.pt for D2

For Model 3.1: Checkpoint Model  3.1COMBINE.pt for D1 and Checkpoint Model 3.1FSD.pt for D2

For Model 3.2: Checkpoint Model  3.2COMBINE.pt for D1 and Checkpoint Model 3.2FSD.pt for D2

For Model 3.3: Checkpoint Model  3.3COMBINE.pt for D1 and Checkpoint Model 3.3FSD.pt for D2

For Model 3.4: Checkpoint Model  3.4COMBINE.pt for D1 and Checkpoint Model 3.4FSD.pt for D2




