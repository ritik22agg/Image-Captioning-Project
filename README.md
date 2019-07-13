<h1> <strong>Image-Captioning-Project </strong> </h1>

<p > This Project is build using Neural Network. This Project takes an image as input and generates a description or caption using it</p>

<h1> <strong> Dataset And Intermediate Data Drive link </strong> </h1>

  <ul>
  <li><strong> Flicker8k_Dataset : </strong> https://www.kaggle.com/ming666/flicker8k-dataset</li>
  <li><strong>Images.npy : </strong>https://drive.google.com/open?id=1-JmbALCZ9a6ZjMzOO8fgChEiW9YvNZNb</li>
  <li><strong>Captions.npy : </strong> https://drive.google.com/open?id=1-JmbALCZ9a6ZjMzOO8fgChEiW9YvNZNb</li>
  <li><strong>Next_word.npy : </strong>https://drive.google.com/open?id=1-GTdWER36WOd_ieAUsjvylj8gZR0A3iF</li>
  </ul>

<h1> <strong> DESIGN </strong> </h1>

<p> This Project consists of various neural models. The different type of model used are :-</p>

<ul>
  <li> <strong> Resnet Model : </strong> This model converts the Images into a 2d array and extract 2048 features.
  <li> <strong> Language Model : </strong> This model consist of LSTM cells and then convert text into 128 feature</li>
  <li> <strong> Image Model : </strong> This model process 2048 features of each image and convert it into 128 features. </li>
  <li> <strong> Combined Model : </strong> This model combines both Language and Image model.</li>
</ul>


<h1><strong> EXAMPLE OF WORKING </strong> </h1>
<img src = "result.JPG">
