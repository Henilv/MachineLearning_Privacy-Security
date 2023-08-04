# MachineLearning_Privacy-Security
ML: Adversarial FMNIST &amp; Machine Unlearning

Adversarial attacks are a class of attacks that show how ML has its flaws and the system can be spoofed.

Machine unlearning performs the task of deletion of datapoints from a trained model and the trade-off between accuracy and utility of such a model, this stems from gdpr regulation which lets users delete their data.



nb1 MNIST-like dataset of 70,000 28x28 labeled fashion images.
 
The images are 28x28 NumPy arrays, with pixel values ranging from 0 to 255. The labels are an array of integers, ranging from 0 to 9. These correspond to the class of clothing the image represents:

Label Class
	•	0 T-shirt/top
	•	1 Trouser
	•	2 Pullover
	•	3 Dress
	•	4 Coat
	•	5 Sandal
	•	6 Shirt
	•	7 Sneaker
	•	8 Bag
	•	9 Ankle boot
	•	Each image is mapped to a single label. Since the class names are not included with the dataset, store them here to use later when plotting the images:
 
 
After this I have written the attack class and method before training the model and launching our attacks, after downloading all dependencies the notebook should be executed in order to generate a sequence of outputs such as follows: 


 
 
1)    Accuracy score vs Epsilon, here we see as the number of epsilon will increase our accuracy will reduce.


2)    The second output shows per epsilon step an how on the 16th epsilon we achieve our goal of fooling the system. 

 
3)    Compare it w epsilon 1 vs 16: Here we see how fake label is given with confidence.

￼
4)    The last part of notebook will give an accuracy breakdown of our approach with other existing approach and a plot of natural and non-natural fooling targets.

