# RNN-LSTM-CNN-BiLSTM
A Comparative study on RNN, LSTM, CNN and BiLSTM models Acoustic Doppler Current Profiler (ADCP) sensor Timeseries Prediction

#### RNN (Recurrent Neural Network):
- RNN is a type of neural network that processes sequential data by maintaining a hidden state and feeding it back as input for the next step.
- It suffers from the vanishing gradient problem, where the model struggles to capture long-range dependencies in the input sequence.
- RNNs are suitable for tasks where the context from previous steps is essential, such as language modeling or sentiment analysis.

#### LSTM (Long Short-Term Memory):
- LSTM is an extension of RNN that addresses the vanishing gradient problem.
- It introduces memory cells with gating mechanisms, which allow the model to learn when to forget or remember information from previous steps.
- LSTMs are effective in capturing long-term dependencies and have been widely used for tasks like machine translation, speech recognition, and text generation.

#### CNN (Convolutional Neural Network):
- CNN is primarily used for image analysis, but it can also be applied to sequential data.
- CNNs leverage convolutional layers to extract local patterns or features from the input data.
- In NLP, CNNs can be used for tasks like text classification or sentiment analysis by treating words as local features and applying convolutions over them.
- CNNs are computationally efficient and can capture local patterns effectively, but they may struggle with capturing long-range dependencies in sequences.

#### BiLSTM (Bidirectional Long Short-Term Memory):
- BiLSTM combines the power of LSTMs with bidirectional processing.
- It processes the input sequence in both forward and backward directions, capturing information from past and future contexts simultaneously.
- BiLSTMs are useful for tasks where both past and future information is important, such as named entity recognition, sentiment analysis, or question answering.
- They are capable of capturing both short-term and long-term dependencies effectively.

#### Counclusion
To estimate the ocean current speed measured by ADCP (Acoustic Doppler Current Profiler), several Deep Learning models were put to the test. The CNN and Bi-LSTM were found to fit the data the best, with r2 values of 0.89 and 0.90, respectively. When model complexity is considered, Bi-LSTM looks to be the best option for predicting ocean current speed because it is less complex than CNN.
https://github.com/AtchayaPraba/RNN-LSTM-BiLSTM.git
