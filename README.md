# vocabulary_builder
Improve vocabulary ability using text data and vocabulary words.  The objective is to be able to substitute words with vocabulary you want to practice with.

## Background Context
As a grad school student, I had to take my GREs in order to get in.  One of the sections I had a tough time working on is vocabulary.  At the time, I looked at the problem with one of two main ways to learn:
1) Do flash cards and memorize as many words
2) Read lots of books and identify name words you've never seen before and practice them!

My approach was a hybrid of the two where I studied flash cards (but would forget ~60-70% of the 1000 words I was memorizing) then read a new book every two weeks.  The problem with reading a book is I'd recognize a GRE vocab word every 3-4 pages.  This means if I'm reading a 250pg book with 250-300 words per page, that means roughly 100 words or ~0.1% of the words I was reading were unfamiliar words.  If I could get 10 books with 100 new unique GRE words, that's 5 months of reading to becpme prepared for my exam..quite inefficient way to get these words engrained in my memory!  In the end, I spend roughly 3 months studying the reading section only to barely squeak by.

<b>Light Bulb Idea</b> Why can't I just build a tool that takes words I don't know, identifies all words and their similarity to this new word, determine context to the passage to ensure the word a verb, and ensure that it's appropriate to substitute the word?

If this is doable, I could allow the user to <i>dial</i> up or down how much vocabulary they want to see in the passage?  If they they want 1-2% of all their words to be GRE vocabulary words, we can do this (but assume more False Negatives and False Positives will occur).  Additionally we'd want to train a Neural Network on this to ensure over time that the system identifies sentence context/patterns which can be used when introducing new vocabulary words.

## Steps Took
* I explored Word2Vec, XXX, and XXX to get an understanding for how I could split up words, identify similiarities, etc
* Built functions which could look up all similiaries and dissimilarities, determine context, etc


