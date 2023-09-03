# IngredientCheck

Contains some of the artifacts and files from the final project of the Deep Learning course (APS360) I took. <br />
In APS360, I worked with a team of other Engineering Science students to create a machine learning model that predicts what ingredients are present in a photo of food. For example, if the model was given a picture of a hotdog, it might say, "pork, bread, tomatoes (ketchup)".

### Challenges <br />
This is an interesting project that goes beyond just basic classification because the model needs to learn about relationships between ingredients to accurately predict ones that are not immediately visible. For example, pepper may not be a visible ingredient, but it is used in many dishes. Another nuance is that each dish will generally have multiple ingredients that need to be classified and there are an incredibly large number of possible ingredients that the model can choose from. This makes it difficult to gather data for every ingredient, train the model, and assess it. Furthermore, we faced several data collection and data processing challenges because images of food are often highly edited, highly artifical, and labels for ingredients are very inconsistent (e.g. one ingredient may be phrased in several different ways and unnecessary details like "fresh" are often used). 

### Architecture <br />
We relied on a convolutional neural network (CNN) to tackle this task and after a lot of experimentation, we found that a VGG-like architecture worked well to solve the problem given the limited resources we had available through Google Colab. 

### Results <br />
Overall, we achieved an accuracy of 81.4%. Although this accuracy is not incredibly high, we are happy with our results because it is a difficult problem and previous attempts at similar problems by other researchers achieved similar or lower accuracies than our model while using much larger architectures through transfer learning.

Our report presents background information, our data collection and processing, a baseline multi-label kNN model, quantitative and qualitative results, discussion, and ethical implications.

Credit to: Julia Ye, Kevin Qu, and Henry Zhang

### Sample Predictions <br />
![image](https://github.com/YangXu-0/IngredientCheck/assets/82414709/1a910594-6ade-4357-b3dd-ad308dd8f168)

