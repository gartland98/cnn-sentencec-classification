# cnn-sentencec-classification

Data Format Summary 

- rt-polaritydata.tar.gz: contains this readme and two data files that
  were used in the experiments described in Pang/Lee ACL 2005.

  Specifically: 
  * rt-polarity.pos contains 5331 positive snippets
  * rt-polarity.neg contains 5331 negative snippets

  Each line in these two files corresponds to a single snippet (usually
  containing roughly one single sentence); all snippets are down-cased.  
  The snippets were labeled automatically, as described below (see 
  section "Label Decision").

  Note: The original source files from which the data in
  rt-polaritydata.tar.gz was derived can be found in the subjective
  part (Rotten Tomatoes pages) of subjectivity_html.tar.gz (released 
  with subjectivity dataset v1.0).

   
=======

Label Decision 

We assumed snippets (from Rotten Tomatoes webpages) for reviews marked with 
``fresh'' are positive, and those for reviews marked with ``rotten'' are negative.
