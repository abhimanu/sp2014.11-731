I have implemented the following:
1. BLEU score 
2. n_gram precision, recall and f-score
3. normal precision and recall  and f-score
4. Truncated precision and recall: Here I compute the precisiona and recall of truncated words to certain length (e.g. 6)
5. Number of characters exactly matched: Here I compute the exact match of the character from the begining for hyp and ref untill the first mismatch.

I tried various things after just doing token recall I got a tau of 0.168. I adding trucated token recall and lot of weighted
avg. recall between simple recall and truncated recall I got a tau of 0.174. After adding number of characters exactly matched
I got a recall of 0.1756

The feature set that give best result is: 1) normal recall, 2) trucated recall with tuncation length 3, and 3) Numbers of chracters matched exactly.
