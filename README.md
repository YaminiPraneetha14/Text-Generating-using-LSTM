# Text-Generating-using-LSTM
Using Recurrent Neural Networks to predict the next word in a sequence given the previous words

LSTM stands for Long Short-Term Memory and is a type of recurrent neural network (RNN) that can be used for generating text.

In text generation using LSTM, the network is trained on a large corpus of text and learns to predict the probability distribution of the next word in a sequence given the previous words. The LSTM model is able to capture long-term dependencies and patterns in the input text.

Once the model is trained, it can be used to generate new text by taking a seed sequence of words and predicting the next word in the sequence. This predicted word is then appended to the seed sequence, and the process is repeated iteratively to generate a longer sequence of words.

LSTM-based text generation is widely used in various applications, including language translation, chatbots, and speech recognition, and has the potential to improve these applications by generating more human-like responses.

This particular notebook is using Nietzsche's writings to generate the text sequences.
