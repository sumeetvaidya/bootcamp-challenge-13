# bootcamp-challenge-13 : Venture Funding with Deep Learning

Alphabet Soup’s business team receives many funding applications from startups every day. The goal is to create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The input is a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. The goal is to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.

## Technologies 
<br/>
The project is written in python and uses the sklearn and tensorflow modules.
<br/>


## Installation Guide  
<br/>
To install the program, download the git repo and run the Jupyter notebook
<br/>

<br/>

## Results
<br/>
There are three models that are used for analysis. <br/>
* Model  uses loss function Binary Crossentropy with 50 epochs and has a loss rate of 55% and accuracy of 73%. <br/>
* Alternate Model 1 uses loss function Mean Squared Error with 50 epochs and has a loss rate of 18.5% and accuracy of 73% <br/>
* Alternate Model 2 uses loss function of Mean Square Logarithmic Eror with 25 epochs and has a loss rate of 9% and accuracy of 73% <br/>
<br/>

| Name  |  Loss Function |  Epochs |  Number of Layers |  Loss Rate |  Accuracy |
|---|---|---|---|---|---|
|  Model | Binary Crossentropy  | 50  | 3  | 55%  | 73%  |
|  Alternate Model 1 | Mean Squared Error  | 50  | 2  | 18.5%  | 73%  |
|  Alternate Model 2 | Mean Square Logarithmic Eror  | 25  | 2  | 9%  | 73%  |
<br/>

## Contributors 
<br/>
Author: Sumeet Vaidya
<br/>
Contributors: BootCamp for providing the base code.
<br/>


## License 
<br/>
When you share a project on a repository, especially a public one, it's important to choose the right license to specify what others can and can't with your source code and files. Use this section to include the license you want to use.

