# Enhancing Collective Estimates by Aggregating Cardinal and Ordinal Inputs
Github repository containing the web application and anonymized data for "Enhancing Collective Estimates by Aggregating Cardinal and Ordinal Inputs", featured in The 8th AAAI Conference on Human Computation and Crowdsourcing 

## Data

Data from the study is in json format and can be found in the "data" folder. The data is structured as follows:

  frames (int) : The problem size of the question. For example, if the problem showed the participant 2 images at a time, this value will be 2. 
  
  rankings (list) : The order in which the participant ranked the images, with 1 representing the image with the least dots, and 5 being the image with the most dots. A perfectly ranked set of 5 images from least to greatest would be [5,4,3,2,1]. 
  
  ratings (list): All of the individual numberical estimations for all images in each problem. These are structed in a way where at position 0 contains the numerical estimation the participant provided for the image with the least amount of dots, and the last position contatins the numerical estimation that the participant provided for the image with the most amount of dots. 
  
  groundtruth (list): The groundtruth numerical estimations for the number of dots in each problem. 
