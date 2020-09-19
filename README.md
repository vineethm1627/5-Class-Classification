# 5-Class-Classification using CNN.
Final Project for Deep Learning Bootcamp :  <a href = "https://www.dphi.tech" > <button> Dphi Website </button> </a>
<h2>About the Data : </h2>
<hr>
The training dataset consists of about 9k medium quality animal images belonging to 5 categories: <br>
butterfly, sheep, cow, squirrel, elephant. <br>
mucca (cow), pecora (sheep), elefante (elephant), farfalla (butterfly) and scoiattolo (squirrel). <br>
All the images have been collected from "google images" and have been checked by human. There is some erroneous data to simulate real conditions (eg. images taken by users of your app).
<hr>
<h2>Dataset Link : </h2> <a href = "https://drive.google.com/file/d/176E-pLhoxTgWsJ3MeoJQV_GXczIA6g8D/view?usp=sharing"> <button> Dataset </button> </a>
<hr>
<h2>Structure of the dataset : </h2>
<hr>
1) train - contains five folders each folder containing images around 1000 to 2000 of those 5 five animals. <br>
   Each image has a unique name. <br>
2) test - contains 910 random images of those 5 animals whose predictions you are to submit on DPhi platform. <br>
3) Testing_set_animals.csv - this is the order of the predictions for each image that is to be submitted on the platform. <br>
    Make sure the predictions you download are with their image’s filename in the same order as given in this file. <br>
<hr>
<br>
<h2> Running the model </h2>
<hr>
<h2> Code : </h2> 
   from tensorflow.keras.models import load_model <br>

loading the model weights <br>
   model = load_model('CNN_model.h5') <br>

<hr>
<h3> Note : </h3>
   Reshape the test image to (100, 100, 1) to do the prediction using CNN model.




 
