

LSTM-RNN: Next-Word Prediction on Hamlet

Train a word-level LSTM to predict what comes next in Shakespeare’s Hamlet.

Highlights
	•	Preprocessing: Cleans and tokenizes Hamlet, builds n-gram sequences.
	•	Model: Embedding → LSTM → Softmax for next-word prediction.
	•	Training: Trained on contextual sequences to learn Shakespearean phrasing.
	•	Generation: Sample with temperature to generate text from a seed phrase.

Get started

pip install tensorflow nltk numpy
python app.py  # run text 