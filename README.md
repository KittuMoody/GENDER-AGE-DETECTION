# GENDER-AGE-DETECTION 
# A project by Kritika and Mudrika
A PYTHON GENDER AND AGE DETECTION PROGRAM
We tackled the problem of classifying a person’s age and gender based on an image. Potential uses of this application include uses in dating sites and social media, access to age-restricted content and for checkout at grocery stores when buying alcohol at the self-checkout.
To build a gender and age detector that can approximately guess the gender and age of the person (face) in a picture using Deep Learning on the Adience dataset.
Adience dataset, this dataset serves as a benchmark for face photos and is inclusive of various real-world imaging conditions like noise, lighting, pose, and appearance. The images have been collected from Flickr albums and distributed under the Creative Commons (CC) license. It has a total of 26,580 photos of 2,284 subjects in eight age ranges (as mentioned above) and is about 1GB in size.
OpenCV is a library of programming functions mainly aimed at real-time computer vision.
We use the argparse library to create an argument parser so we can get the image argument from the command prompt. We make it parse the argument holding the path to the image to classify gender and age for.
The predicted gender may be one of ‘Male’ and ‘Female’, and the predicted age may be one of the following ranges- (0 – 2), (4 – 6), (8 – 12), (15 – 20), (25 – 32), (38 – 43), (48 – 53), (60 – 100) (8 nodes in the final softmax layer). It is very difficult to accurately guess an exact age from a single image because of factors like makeup, lighting, obstructions, and facial expressions. And so, we make this a classification problem instead of making it one of regression.
Once you start treating age prediction as a regression problem, it becomes significantly harder for a model to accurately predict a single value representing that person’s image.
However, if you treat it as a classification problem, defining buckets/age brackets for the model, our age predictor model becomes easier to train, often yielding substantially higher accuracy than regression-based prediction alone.
The process of visual age prediction is difficult, and I’d consider it subjective when either a computer or a person tries to guess someone’s age.
In order to evaluate an age detector, you cannot rely on the person’s actual age. Instead, you need to measure the accuracy between the predicted age and the perceived age.
Here is the link for the caffemodles used in the project-:
https://drive.google.com/drive/folders/1Njq70wIi1fEVrBNWMItMpVPoq4b51_WD?usp=sharing



