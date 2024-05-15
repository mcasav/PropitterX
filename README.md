# PropitterX

PropitterX is a Twitter propaganda corpus, with 385,391 tweets.

Content
--------------------------------------------
PropitterX dataset includes Train (trainSet_21 and trainSet_17), Development and Test sets with labels.

The files 'trainSet_21_part1' and 'trainSet_21_part2' (split in two parts due to size constraints) contains the following columns:

Col 1. Post ID
Col 2. Label ('0' for no-propaganda, '1' for propaganda)
Col 3. Temporal_split (indicates the temporal partition of the post for 'PropitterX-TIME')
Col 4. Bias
Col 5. Region
Col 6. emotionLabel (predominant emotion evoked in the post, predicted by a model fine-tuned with a sentiment analysis dataset)
Col 7~13. Individual probabilities per emotion (neutral, surprise, joy, fear, sadness, disgust, anger), calculated by the model fine-tuned with a sentiment analysis dataset.

The files 'trainSet_17', 'devSet', and 'testSet' contain the following columns:

Col 1. Post ID
Col 2. Label ('0' for no-propaganda, '1' for propaganda)
Col 3. Bias
Col 4. Region
Col 5. emotionLabel (predominant emotion evoked in the post, predicted by a model fine-tuned with a sentiment analysis dataset)
Col 6~12. Individual probabilities per emotion (neutral, surprise, joy, fear, sadness, disgust, anger), calculated by the model fine-tuned with a sentiment analysis dataset.
--------------------------------------------


Citation 
--------------------------------------------
​
Please cite the following publication when using PropitterX:

TBD
--------------------------------------------
