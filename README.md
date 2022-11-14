# IBM-Project-34128-1660231910
# AI-powered Nutrition Analyzer for Fitness Enthusiasts
![topic](https://user-images.githubusercontent.com/113708413/201635357-cd5a1e30-fcf3-4d00-95ea-823280d8c058.png)
# GOAL
Creating an AI-Powered Nutrition Analyzer for Fitness Enthusiasists to Know the Nutrition content present in the food
# TEAM MEMBERS
1. KEERTHANA R[TL] - 612919104029              
2. NAVEENA T[TM1] -612919104035
3. PRABA K[TM2] - 612919104039
4. GOWRI S[TM3] - 612919104022
 
![cycling_](https://user-images.githubusercontent.com/113708413/201638803-387ce02a-dbb5-4c82-bf6b-a4ec58f714c2.gif)
# INTRODUCTION
  Food is essential for human life and has been the concern of many healthcare conventions. Nowadays 
new dietary assessment and nutrition analysis tools enable more opportunities to help people understand 
their daily eating habits, exploring nutrition patterns and maintain a healthy diet. Nutritional analysis
is the process of determining the nutritional content of food. It is a vital part of analytical chemistry
that provides information about the chemical composition, processing, quality control and contamination of food.

  The main aim of the project is to building a model which is used for classifying the fruit depends on the 
different characteristics like colour, shape, texture etc. Here the user can capture the images of different 
fruits and then the image will be sent the trained model. The model analyses the image and detect the nutrition 
based on the fruits like (Sugar, Fibre, Protein, Calories, etc.).
# PROJECT OBJECTIVE
**By the end of this project you will**
➼ Know fundamental concepts and techniques of Convolutional Neural Network.

➼ Gain a broad understanding of image data.

➼ Know how to pre-process/clean the data using different data preprocessing techniques.

➼ Know how to build a web application using Flask framework.
# PROBLEM STATEMENT
  The main problem faced by fitness enthusiasts is tracking their daily nutrition intake which is important to 
stay fit. But in today's bustling society and availability of abundant resources online about fitness, tracking 
nutrition will become more challenging and inaccurate. Fitness enthusiasts normally follow their diet plans but 
they struggle tracking nutritional contents of the food. Fruits are rich in vitamins, fibers, and minerals which
makes them easily digestible, but over-consumption will result in weight gain and even diabetes as fruit contains 
natural sugar.

  Fitness enthusiasts follow a diet which contains fruits, vegetables, protein rich foods and low carb foods. But
tracking their nutritional contents like fiber, protein and essential nutritions will not be an easy task. Some 
fruits are allergic to some consumers based on their medical condition. Which they need to identify before consuming.
Identifying nutritional values of unknown food and fruit varieties will become impossible without online technologies 
as they have no prior knowledge about them.
# PROJECT FLOW
  User interacts with the UI (User Interface) to upload the image as input

  Depending on the different gesture inputs different operations are applied to the input image.

  Once model analyses the gesture, the prediction with operation applied on image is showcased on the UI.
  **To accomplish this, we have to complete all the activities and tasks listed below**
  ➼ Data Collection.

   Collect the dataset or Create the dataset

➼ Data Preprocessing.

    Import the ImageDataGenerator library
    Configure ImageDataGenerator class
    Apply ImageDataGenerator functionality to Trainset and Testset

➼ Model Building

    Import the model building Libraries
    Initializing the model
    Adding Input Layer\
    Adding Hidden Layer
    Adding Output Layer
    Configure the Learning Process
    Training and testing the model
    Save the Model

➼ Application Building

    Create an HTML file
    Build Python Code
 # PROJECT STRUCTURE
 ![dataset](https://user-images.githubusercontent.com/113708413/201641334-391eb587-5367-4efa-ab3b-d27df2221071.png)
  **Create a Project folder which contains files as shown below**
  -Dataset folder contains the training and testing images for training our model.
-We are building a Flask Application that needs  HTML pages stored in the templates folder and a python script app.py for serverside scripting
-we need the model which is saved and the saved model in this content is a nutrition.h5
-templates folder contains home.html, image.html, imageprediction.html pages.
-Statis folder had the css and js files which are necessary for styling the html page and for executing the actions.
-Uploads folder will have the uploaded images(which are already tested).
-Sample_images will have the images which are used to test or upload.
-Training folder contains the trained model file.
# TECHNICAL ARCHITECTURE
![architecture](https://user-images.githubusercontent.com/113708413/201641883-83534f86-ba96-4018-bc3a-49f7a5cdbcf8.png)

 



