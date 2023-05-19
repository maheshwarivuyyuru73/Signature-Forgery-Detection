 Signature and forgery detection using convolutional neural network
 
Abstract:

Signatures are veritably important in our social and legal life for verification and authentication. A hand can be accepted only if it's from the intended person. The probability of two autographs made by the same person being the same is veritably less. Numerous parcels of the hand may vary indeed when two autographs are made by the same person. So, detecting a phony becomes a grueling task. In this paper, a result grounded on Convolutional Neural Network (CNN) is presented where the model is trained with a dataset of autographs, and prognostications are made as to whether a handed hand is genuine or forged.and also we are using harris technique for the corner detection step to give better input features to the algorithm of convolutional neural network. Using step signature forgery detection is simple.

1.INTRODUCTION

Signature verification and forgery detection is the process of verifying signatures automatically and instantly to determine whether the signature is real or not. There are two main kinds of signature verification: static and dynamic. Static, or off-line verification is the process of verifying a document signature after it has been made, while dynamic or on-line verification takes place as a person creates his/her signature on a digital tablet or a similar device. The signature in question is then compared to previous samples of that person's signature, which set up the database. In the case handwritten signature on a document, the computer needs the samples to be scanned for investigation, whereas a digital signature which is already stored in a data format can be used for signature verification. Handwritten signature is one of the most generally accepted personal attributes for verification with identity whether it may for banking or business [1,2]. There are several verification methods for offline signature verification which most of the companies use nowadays. Offline signatures use the static features of the system which involves image processing techniques to analyses the accuracy of the signatures. These include the initial identification of a person through the password. There are other multimodal systems that use the two different biometric features in order to strictly authenticate a person's identity. 

Existing method:

In existing methodology they used with the machine learning algorithms and they did like prediction levels with the data set but not clear weather that signature is forgery or not. They did with critical modules but result not found properly.we are facing these type of problems in bank checks and in different business applications. Basically, signature verification is very big problem in all type of applications.

Drawbacks:
•	Signature forgery is not good
•	Features not identified properly

Proposed method:

In this proposed methodology we are using better techniques and algorithms to identify and find out of forgery detection in signatures. For that we introduced convolutional neural network and harris technique to get better results. here, data set trained by convolutional neural network.so, forgery detection is easy with model classification.


Advantages:

•	Forgery detection of signatures are easy.
•	Trained by better algorithm

Applications:

•	Forensic applications
•	Banking applications
•	Business applications

Modules:

•	image acquisition:

In image processing, image acquisition is an action of retrieving image from an external source for further processing. It's always the foundation step in the workflow since no process is available before obtaining an image.

•	Pre-processing :

in this step we have to reduce the complexity of the picture of license plate using resize and the conversion.using these pre-process we can change the size of the license plate using resize.

•	Train and test:

Train/ Test is a system to measure the delicacy of your model. It's called Train/ Test because you resolve the the data set into two sets a training set and a testing set. 80 for training, and 20 for testing. You train the model using the training set. You test the model using the testing set. 


•	CNN:

in deep literacy, a convolutional neural network (CNN/ ConvNet) is a class of deep neural networks, utmost generally applied to dissect visual imagery. Now when we suppose of a neural network we suppose about matrix proliferations but that isn't the case with ConvNet. It uses a special fashion called Convolution.



•	Validation and accuracy:

How the model is able to classify the images with the validation dataset. ( A validation dataset is a sample of data held back from training your model that is used to give an estimate of model skill while training the model).


CONCLUSION:

The network gave about an delicacy of data on the test set, which is relatively considerable I guess. This whole work was done for an online competition though I did n’t get through but it gave a lot of experience and I hereby apologize for all the spelling miscalculations and grammatical crimes I did throughout this blog, thanks for bearing.
For the future analysis from the video also we can do the same process with more accuracy.








