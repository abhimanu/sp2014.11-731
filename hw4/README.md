I implemented Pairwise Ranking optimization.
Then for the challenge part I extracted length of the hypothesis and untranslated word features
I included BLEU and RECALL as the scores.
I trained a NB classifier and reported the score over it

To run the code 
./rerank > test.trans
./score-meteor < test.trans


