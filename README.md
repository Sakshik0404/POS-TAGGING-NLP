# POS-TAGGING-NLP

HMMs and Viterbi algorithm for POS tagging.

## Problem Statement
  - Write the vanilla Viterbi algorithm for assigning POS tags (i.e. without dealing with unknown words) 
  
  - Solve the problem of unknown words using at least two techniques. These techniques can use any of the approaches discussed in 
  the class - lexicon, rule-based, probabilistic etc. Note that to implement these techniques, you can either write separate functions 
  and call them from the main Viterbi algorithm, or modify the Viterbi algorithm, or both.
  
  - Compare the tagging accuracy after making these modifications with the vanilla Viterbi algorithm.
  
  - List down at least three cases from the sample test file (i.e. unknown word-tag pairs) which were incorrectly tagged by the 
  original Viterbi POS tagger and got corrected after your modifications.

  ## saving ml model to pkl
   after devloping a model for pos tagging we can save that model to pkl file so we do not need to perform testing again this saves our time 

  Save the model to pkl file by using dill 
