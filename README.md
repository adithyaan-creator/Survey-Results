# Survey-Results

The analysis done is for a group of 10 people based on their responses to Big5 personality questionnaire.

The data being categorical/non numerical with upto maximum of 5 responses, coming up with predictng a rating might not be feasible. So what has been done is a 
similarity study of how similar are the people based on their responses. The results are quite good considering 10 data points, and we can improve results with 
more data points, if it can generalize well to the population the better.

The steps taken are to convert the response variables to numerical values, which is done by converting each response of a question to a corresponding column. 
  Considering the case of Column 'Am interested in people.', there are 5 individual values. So the encoded file will contain 5 column with values being 0 and 1 
to corresponding value of response.
  After encoding, the dimensionality[Number of features] increases, making visualization and understanding data difficult. To mitigate this, the principal 
components[2 components] has been found and visualized. The visualizations has been done for Agreeableness, Extrovertion and conscientiousness.

![Alt text](https://github.com/adithyaan-creator/Survey-Results/blob/master/agreeablenessViz.jpg)
