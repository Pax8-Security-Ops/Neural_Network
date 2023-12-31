## Introduction 

There are two different paths to take when creating a neural net intended for our purposes. However, I think the ideal final product should include elements from both. 

### 1) The Bootstrapping Method: 
_Overview_: A portion of the CSV image split off from the main data frame and retasked to form randomly-generated training samples based off the CSV dataframe introduced to the network. The samples would be fed through the neural network a certain amount of times determined by the programmer. Each time the samples are fed through, they create a produce a prediction as close to the desired conclusion as possible. The final physical conclusion is calculated when the neural net averages all predictions.

_Problem:_ In order for this method to work, the data that will be used to train the neural net must be seperated into two categories using Binary Classification. The first time I utilized this method, the dataset we used had a column labeled 'dataset', comprising two numbers. In our case, these numbers would be used to seperate normal network traffic and bad traffic. Unfortunately, I don't know how the dataset I used before back in class was given the 'dataset' column or even where the data set came from. My instructor provided it to the class and I can't remember his source. Furthermore, I don't know how to replicate that same column and it's mechanics in the form of a search query for Sumo Logic. 

### 2) Recurrent Neural Network: 
_Overview_: Initial used for analysis on time-based dataframes, the RNN is the closest method I could find that involved a close mechanic for a neural net to accomadate constant streams of data. This method comes in the form of a for-loop included with the physical coding line the neural net uses to process data and formulate it's conclusions through the nodes. This component is called the hidden layer. 

_Problem_: Due to lack of prior knowledge or experience with using RNNs, the actual neural net I'm building to utilize this method is incomplete. There have been a number of error messages coming up every time I try to activiate the neural net and feed it data. And it has led me down a troubleshooting rabbit hole that not even ChatGPT can seem to get me out of. 
