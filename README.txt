How to run the project:

Step 1) Clone all project files from Github

Step 2) Download Glove (word embeddings) from https://nlp.stanford.edu/projects/glove/ and add it to the project folder (I could not upload it to GitHub as it exceeds GitHubs file size limit).

Step 3) Run the NER.ipynb file. I used many python libraries for this project, if you do not have them installed you will have to install them on your machine first.

I have commented out the parts of my code that involve training the Convolutional Neural Network and Maximum Entropy Markov Model, since those take a long time to train. Instead I have included files with the models saved on them, and then in my code I just load these models. 