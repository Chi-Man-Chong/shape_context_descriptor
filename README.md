# Shape Context Descriptor: A New Approach to Assess Consistency of Two Correlated Land Boundaries

Vincent Chong  
chi-man.chong@connect.polyu.hk  
July 6, 2020  
A computer vision algorithm used in my dissertation, which was submitted to the Hong Kong Polytechnic University in partial fulfillment of the requirement for the degree of Bachelor of Science (Honours) in the Program of Geomatics  
Instructed by Dr. Yan Wai-yeung  

## Abstract
This dissertation presents a new approach for the correlating land boundaries using shape context descriptor. Boundary correlation is one of the important steps in the land boundary re-establishment in Hong Kong. In the current practise, the consistency between two correlated boundaries is assessed by human interpretation. It is more likely a subjective approach. Therefore, I explore the use of shape context to correlate the boundaries in land records. It aims to assist the land surveyors for their interpretation. The boundary of the same lot in two land records can be identified and matched based on its geometry. A coordinate transformation model can be established using the matched vertices of the two boundaries. Least squares adjustment is used to estimate the model coefficients. Accuracy assessment of the result can be performed by Dice Similarity Coefficient (DSC).

## Folders
* **code**: Python script for the shape context descriptor for correlating Land Boundaries
* **paper**: The dissertation (in .pdf format)

## Installation
1. Download and install [Python 3.8](https://www.python.org/downloads/)  
2. Download the [code]()
3. Download the sample inside [experiment]() for testing (optional) 
