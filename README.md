# composer-classifier-lstm
Classifying classical composers using MIDI data and LSTM-based neural networks
# Composer Classification from MIDI Files

This project uses a deep learning approach to classify classical music compositions by composer. MIDI files are preprocessed into token sequences, augmented through transposition, and passed into a Bidirectional LSTM model for classification. The dataset includes works from nine composers, and the model achieves over 60% test accuracy.

## Features
- MIDI data preprocessing using `music21`
- Tokenization and sequence padding
- Data augmentation with semitone transposition
- Bidirectional LSTM model with embedding layer
- Evaluation using accuracy, confusion matrix, and classification report

## Technologies
- Python
- TensorFlow / Keras
- Scikit-learn
- Music21

## Results
Final test accuracy: ~61%  
Model shows strong precision/recall on composers like Chopin and Byrd, with room for improvement on others like Handel and Hummel.

## How to Run
1. Upload your `composer_dataset.zip` to the Colab environment
2. Follow the notebook cells in order or load the preprocessed data from the `.npz` file
3. Train the model or load weights as needed

## License
This project is for educational purposes.
