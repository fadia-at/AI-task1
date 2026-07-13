This project is a simple AI model I built to recognize images and classify them into two categories: Electronics and Toys.

Classes Chosen
I trained the model to classify items that are commonly found around me:
1. Electronics:Such as smartphones, laptops , playstation.
2. Toys:Such as toy car , doll.

How I Completed the Task?

1. Training:I used Google Teachable Machine to capture and collect images for each class (about 4 images per category) so the model could learn the differences. After testing and verifying its accuracy, I downloaded the trained model files in Keras format.
2. Coding (Google Colab):I wrote a Python script in Google Colab, uploaded the model files, and tested it with a sample image. The script resizes the image to fit the model's required dimensions and outputs the final prediction along with the confidence score.

Results
The model works perfectly! It accurately recognizes the provided images, then prints the predicted class name and the confidence score in the output terminal.
