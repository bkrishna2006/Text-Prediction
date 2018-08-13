# Text-Prediction
3  Text Prediction Modelling.
	1. Preparing unique n-gram frequency and probability table for each of the ngrams
	2. Drop the n-grams where the probability is extremely low (close to 0)
	3. Split each of the unique n-grams into "n-1 gram" and "predicted next word"
	4. Combine all n-gram tables containing n-1grams, predicted-next-word, freq & prob into a single look-up table.
<Note> This program, creates a All-gram look up table, for predictions.
