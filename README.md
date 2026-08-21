Fashion recommendation system

In this end to end project, I have made a fashion recommendation system using Resnet50. I have used a dataset 44441 images which I downloaded from kaggle.
First I 2048 features from each image using Resnet50. These features are in an array.
Then I made an streamlit app in which user will upload any image, Resnet50 will extract features from that image and store it in array.
I used nearest neighbors algorithm to retrieve top 5 visually similar features from the given input
