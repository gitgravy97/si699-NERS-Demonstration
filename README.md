# si699-NERS-Demonstration
Material from my graduate seminar demo on training custom named-entity recognition system.

I originally prepared this for an approximately about-20-minute lecture presented to a cohort of ~100 terminal 
informatics masters students at the University of Michigan. In overview, we sample data from Reddit and construct a 
customized Named Entity Recognition System (NERS) that "learns" to extract terms under a fitting categorical label 
based on annotated training data "teaching" what each categorical term cluster looks like.

As this is primarily an example pipeline intended for instruction and proof-of-concept, there's enough example data to
get the system operating well enough to have a few success cases shown at the end, but for any serious usage, more 
annotated training data would be necessary.

- `data` contains the final, combined set of annotated data
- Book 1 introduces the PRAW wrapper for the Reddit API, covers data gathering
- Book 2 introduces annotation and default NERS system
- Book 3 finalizes with custom modeling based on the annotated dataset
