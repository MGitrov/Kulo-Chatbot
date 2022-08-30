# Introduction
After I've learned the theory behind the computer vision subfield, I moved to the next subfield which is the natural language processing (NLP), when the main aim of the project was to translate all the theory into something practical in order to strengthen the understanding.

Additional topics that I learned were RNN, LSTM, GRU, and Transformers.

# Data
I set up an Intents.json file that defines certain intentions that could occur during the interactions with the chatbot (Predefined patterns and responses).
The Intents.json structure is as follows:
* Tags: A set of tags (or labels) that user's queries may fall into.
* Patterns: A set of patterns that define the different ways of how a user may ask the question.
* Responses: A set of static responses that the chatbot will randomly choose one of them and return when posed with a query.

The chatbot will take these patterns and use them as training data to determine how it looks when the chatbot is being asked for its name (For instance), so that it could adapt to the different ways the user may ask to know the chatbot's name. Hence, the user will not have to use the exact queries that the chatbot has learnt on.

# Performance
Unlike the computer vision project, here there is not much data to train the neural network on, so I was able to train the neural network along a lot of epochs without any computational restrictions.

The neural network was able to achieve 100% of accuracy on the training data, which means it will be able to generate the corresponding response if the user's input text will be as similar to the patterns the neural network was trained on.

* Accuracy: 16.67% -> 100.00%
* Loss: 1.8099 -> 0.0867

# Demonstration
https://user-images.githubusercontent.com/68182283/187167635-fe8ecab5-692f-423d-953d-990eab3aa150.mp4
