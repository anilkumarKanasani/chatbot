# Developing the bot

#### How to Make Chatbot in Python?

Now we are going to build the chatbot using Python but first, let us see the file structure and the type of files we will be creating:

* **Intents.json –** The data file which has predefined patterns and responses.
* **train\_chatbot.py –** In this Python file, we wrote a script to build the model and train our chatbot.
* **Words.pkl –** This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
* **Classes.pkl –** The classes pickle file contains the list of categories.
* **Chatbot\_model.h5 –** This is the trained model that contains information about the model and has weights of the neurons.
* **Chatgui.py –** This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

Here are the 5 steps to create a chatbot in Python from scratch:

1. [Import and load the data file](import-and-load-the-data-file.md)
2. [Preprocess data](data-preprocessing.md)
3. [Create training and testing data](split-the-data.md)
4. [Build the model](model-building.md)
5. [Predict the response](predict-the-responses.md)



