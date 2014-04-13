I have implemented two methods. 

1. The default scheme with stack size of 100. It gives a score of -5573.696277, better than the 
default score on the leader board.
2. The scheme given by Zens et al. in COLING 2004 paper: 
Reordering constraints for phrase-based statistical machine translation. It has two main parameters to be tuned: a) the 
number of phrase that can be skipped (k) and b) the beam size (b). With a k=21 and b=90 it gives a score of -5076.058658

Run the code by typing:
./decode | ./grade
This has default k=21 and b=90

To change k and bs to for example 19 and 100 respectively type as follows:
./decode -k 19 -b 100 | ./grade



