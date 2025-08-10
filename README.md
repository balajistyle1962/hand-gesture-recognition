# Gesture-Recognition-for-Sign-Language-Translation
This program will use gesture detection to help identify common ASL gestures as well as alphabets, translating them into sentences. These will be converted to speach using Google's TTS library. This application will be converted into a Android application for greater usability.


<br>


<br>

## File Descriptions

- `ML/`: Contains all files realted to data colelction, preprocessing and model training
  - `Model Training.ipynb`: Notebook containing various models and feature engineering techniques to comapre performance.
  - `data/`: Contains the compiled results as well as camera aspect ratio data
  - `model_saves/`: Contains the tensorflow checkpoints for the models trained in `Model Training.ipynb`

- `public/`: Files related to the webpage including the HTML/CSS files for page design aand JS scripts
  - `models/`: TensorflowJS models for the alphabet and gesture models 
 
- `index.js`: Nodejs base file to run the webpage


<br> 





