# int-247-km007-ca-2-Navneet1ss
int-247-km007-ca-2-Navneet1ss created by GitHub Classroom
The problem consists in classifying all the blocks of the page layout of a document that has been detected by a segmentation process. This is an essential step in document analysis in order to separate text from graphic areas. Indeed, the five classes are:
text (1)
horizontal line (2)
picture (3)
vertical line (4)
graphic (5)

Relevant Information Paragraph:<br The 5473 examples comes from 54 distinct documents.
Each observation concerns one block.
All attributes are numeric.
Data are in a format readable by C4.5.

Number of Instances: 5473.

Number of Attributes :
height: integer. | Height of the block.
lenght: integer. | Length of the block.
area: integer. | Area of the block (height * lenght);
eccen: continuous. | Eccentricity of the block (lenght / height);
p_black: continuous. | Percentage of black pixels within the block (blackpix / area);
p_and: continuous. | Percentage of black pixels after the application of the Run Length Smoothing Algorithm (RLSA) (blackand / area);
mean_tr: continuous. | Mean number of white-black transitions (blackpix / wb_trans);
blackpix: integer. | Total number of black pixels in the original bitmap of the block.
blackand: integer. | Total number of black pixels in the bitmap of the block after the RLSA.
wb_trans: integer. | Number of white-black transitions in the original bitmap of the block.
