# int-247-km007-ca-2-Navneet1ss
int-247-km007-ca-2-Navneet1ss created by GitHub Classroom <br>

The problem consists in classifying all the blocks of the page layout of a document that has been detected by a segmentation process. This is an essential step in document analysis in order to separate text from graphic areas. Indeed, the five classes are:<br>
text (1)<br>
horizontal line (2)<br>
picture (3)<br>
vertical line (4)<br>
graphic (5)<br>

Relevant Information Paragraph: The 5473 examples comes from 54 distinct documents.
Each observation concerns one block.
All attributes are numeric.<br>

Number of Instances: 5473.<br>

Number of Attributes :<br>
height: integer. | Height of the block.<br>
lenght: integer. | Length of the block.<br>
area: integer. | Area of the block (height * lenght);<br>
eccen: continuous. | Eccentricity of the block (lenght / height);<br>
p_black: continuous. | Percentage of black pixels within the block (blackpix / area);<br>
p_and: continuous. | Percentage of black pixels after the application of the Run Length Smoothing Algorithm (RLSA) (blackand / area);<br>
mean_tr: continuous. | Mean number of white-black transitions (blackpix / wb_trans);<br>
blackpix: integer. | Total number of black pixels in the original bitmap of the block.<br>
blackand: integer. | Total number of black pixels in the bitmap of the block after the RLSA.<br>
wb_trans: integer. | Number of white-black transitions in the original bitmap of the block.<br>
<br>
Gaussian NB<br>
K-Fold:
That method is known as “k-fold cross validation”. It’s easy to follow and implement. Below are the steps for it:<br>

Randomly split your entire dataset into k”folds”<br>
For each k-fold in dataset, build model on k – 1 folds of the dataset. Then, test the model to check the effectiveness for kth fold<br>
Record the error on each of the predictions<br>
Repeat this until each of the k-folds has served as the test set<br><br>
The average of k recorded errors is called the cross-validation error and will serve as performance metric for the model<br>
<br>
Stratified K-Fold<br>
Stratification is the process of rearranging the data so as to ensure that each fold is a good representative of the whole.
It is generally a better approach when dealing with both bias and variance. A randomly selected fold might not adequately represent the minor class, particularly in cases where there is a huge class imbalance.
