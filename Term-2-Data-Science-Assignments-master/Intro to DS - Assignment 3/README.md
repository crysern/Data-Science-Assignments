# Assignment 3

In this assignment, your task is to find a dataset and see if you can identify and describe some meaningful clusters within it.

Submit a notebook with code showing your exploration, the answers to questions, along with any figures, images or media to support these. I have provided 3 possible notebooks with example code for you to work with, but you should use these with your own dataset.


1. Find a dataset.

It can be structured, numeric data like we have looked at before (Notebook)

OR

If you want to try some media data, I have an image clustering notebook.

OR

You can even try audio clustering with Leon Feddons excellent notebook. (I'd try with just librosa audio features here and avoid wavenet)


2. Pick some variables and visualise as a 2D plot using PCA. Does there appear to be clear groups?


3. Run K-Means and visualise the results. Experiment with some of the things below. It may be that you iterate between this and step 4 a few times, investigating how your clusters are and updating your parameters / dataset.

   Different values of k
    
   Different features (e.g. different columns in your dataset)

   Different dimensionality reductions (e.g run PCA first, then cluster the principal components as opposed to the original features)
    
  Which provides the provides the best clusters? How did you reach this conclusion?
 

4. Investigate the examples in your clusters, do they seem to have coherent differences? If so, can you characterise them? You can try the methods below.

If the clusters seem to have no patterns, can you think why this might be, considering your data, and its representation/features?
Techniques you can use for this are:
   
   Examining representative examples (there is code for comparing top images in clusters against each other, or a larger number of representative images from a single cluster)
    
   Plotting means of features against each other (for numeric data)
