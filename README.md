# Predict-age-gender-and-ethnicity-from-image-using-Deep-Learning
The purpose of this model is to predict a person's age, gender, and ethnicity once provided with a grayscale image of that person.


### Dataset
Dataset that has grayscale images of 48x48 dimensions representing individuals from five ethnic groups. The individuals were also categorized according to gender and annotated with age. The graph mentioned below demonstrates the age distribution within the dataset.
                            ![graph](graph.jpg)

The dataset contains 23479 images divided into train, validation and test folders. The validation and test sets contain 20% of the total dataset. In addition to the grayscale images, are provided with the “age_gender.csv”, which contains the following fields:

Age: age of the individual <br/>
Gender: gender of the individual <br/>
Ethnicity: ethnicity of the individual <br/> 
Img_name: name of the image to be linked with the image in either train, val or test folders <br/>


You can download the materials,
containing the following files and folder. The purpose of each file and folder is
mentioned below:
* data/images/train: Contains the images to be used when training the model <br/>
* data/images/val: Contains the images to be used for validating the model <br/>
* data/images/test: Contains the images to be used as the test data to identify how well your model has generalized <br/>
* code.ipynb: This is the code file <br/>
* model: The folder contain model weights <br/>
* logs: The folder contain tensorboard logs <br/>
