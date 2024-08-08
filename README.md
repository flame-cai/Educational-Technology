# VideoQA - Comprehensive algorithm for an enhanced learning expereince

The VideoQA algorithm aims to embed to perform topic segmentation by leveraging the power of LLMs to divide tutorials/lectures into appropriate topics and genrating relevant questions and answers for the same.

This repository contains the code and the instructions to run the code.

<u> Note:</u> The code is configured to run on google colab for ease of accessibility. The given code requires atleast a T4 GPU connectivity on colab for succesful execution.

Instructions to run the python program in order to generate the desired output is given below:

- Clone this repository and transfer all of the contents in a folder named `VideoQA`.

- Download the [Denoiser-master](https://drive.google.com/drive/folders/15-0XHF_xHw1wR62SV5iJWjg5rjllBYIW?usp=sharing) folder and transfer it in the `VideoQA` folder.

- Download the [pre-trained models](https://drive.google.com/drive/folders/15-0XHF_xHw1wR62SV5iJWjg5rjllBYIW?usp=sharing) folder and transfer it in the `VideoQA` folder. 

- Upload this folder in your google drive.

- Open the `videoqa.ipynb` python notebook using Google Colab and connect the runtime to a `T4 GPU`.

- Run all of the cells in the given notebook. Installing dependencies on colab sometimes requires one to restart the session. If this happens, restart your session from the beginning and keep running the cells.

- After you run the last cell, the youtube URL for the video whose embedded QA output you desire. 

- After entering the youtube URL, the final output will be stored in a folder called `output` in the VideoQA folder in your Google Drive.



A few example videos and their output after using the given algorithm are given in this [folder](https://drive.google.com/drive/folders/1r-4CoDOx3UGmL-jtAylHeDN4TJeCulHL?usp=sharing). 
