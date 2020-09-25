# MachineLearning_GenerativeModelForText
  1. Build a generative model to writing style of Bertrand Russell
  2. Following books are used to build model:
    i. The Problems of philosophy
    ii. The Analysis of Mind
    iii. Mysticism and Logic and Other Essays
    iv. Our Knowledge of the External World as a Field for Scientific Method in Philosophy
  3. All text contents are concatenated excluding header and footer.
  4. Trained the LSTM model using character-level presentation with 256 memory units.
  5. characters are encoded into integer using ascii values and rescaled in [0,1] for LSTM.
  6. Window Size is set to 100 and used one-hot encoding scheme
  7. Used the sigmoid activation function and Softmax output layer
  8. Used to save the model_checkpoint in between improvements.
  9. Generated 1000 characters
