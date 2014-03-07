I have implemented the following:
1. BLEU score 
2. n_gram precision and recall
3. normal precision and recall
4. Truncated precision and recall: Here I compute the precisiona and recall of truncated words to certain length (e.g. 6)
5. Number of characters exactly matched: Here I compute the exact match of the character from the begining for hyp and ref untill the first mismatch.

The feature set that give best result is: 1) normal recall, 2) trucated recall with tuncation length 3, and 3) Numbers of chracters matched exactly.
