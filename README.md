# anomaly-detection

Uses Neural Networks (Autoencoders) and probabilistic clustering (Gaussian Mixture Model) to identify anomalous data points. 
Implemented using TensorFlow, Keras, and Sklearn.

Runs the autoencoder neural net on various types of data - cyber attack dataset, mnist imagery, fraud

## Example output from GMM ran on cyber attack data (3 million observations)

Allows us to prioritize which data points to inspect further, based on a low probability.

****<img width="964" height="551" alt="image" src="https://github.com/user-attachments/assets/5d96431a-c3d6-4d22-897c-ccd017ea60ef" />

<img width="760" height="437" alt="image" src="https://github.com/user-attachments/assets/e043dd36-3688-4ebd-b147-bfd525853f08" />


### GMM classification report:

<img width="430" height="137" alt="image" src="https://github.com/user-attachments/assets/9bb05386-c79c-4c4c-bc98-d6aafca1259a" />



## Example output from Autoencoder model ran on cyber attack data 

<img width="764" height="486" alt="image" src="https://github.com/user-attachments/assets/4a1db0da-cfc1-488a-bdc7-45b48f82b30e" />

<img width="719" height="137" alt="image" src="https://github.com/user-attachments/assets/51656ce2-51ab-409d-bec3-c880c129530a" />
