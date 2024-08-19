The following tasks have been performed by me in the code file:

1. In solution 1 I have done corpus cleaning, and extracting all the words of the file in the array and correcting their unicodes.

2. In solution 2 I found character, syllables & top 20 unigram and bigram frequencies of these characters and syllables.

3. In question 3 I manually identified the word groups of the random 25 sentences assigned to me.

4. In question 4 I trained the following models:

	a. Unigram model on Vocab size 1000
	b. Unigram model on Vocab size 2000
	c. BPE model on Vocab size 1000
	d. BPE model on Vocab size 2000
   Then I found the top 20 unigram and bigram frequencies of characters, tokens and syllables for each tokenizer.

   After this I used the pretrained models
	a. mBERT
	b. IndicBERT
   On Maxlength 1000 and 2000
   Then I found the top 20 unigram and bigram frequencies of characters, tokens and syllables for each tokenizer.

5. In Question 5 I considered tokens obtained in question 3 as ground truth and found the precision, recall, f-score & accuracy for all tokenizers

6. Here I compared the performance metrics of all the above stated tokenizers.