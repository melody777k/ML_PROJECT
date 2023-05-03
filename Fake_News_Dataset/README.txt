
==================================================
Human Activity Phrases with Relational Annotations
==================================================

If you use this dataset, please cite the following paper:
Wilson, Steven R., and Mihalcea, Rada. Measuring Semantic Relations between Human Activities. In Proceedings of the International Joint Conference on Natural Language Processing, 2017. Taipei, Taiwan.

There is a single CSV file that contains all of the data and annotations.

Description of CSV fields:
qid: Question ID. A unique ID for each question. The number before the underscore indicates the group of questions that were shown to mTurk workers together, and the number after the underscore is the item number within the group. Groups contain 25 items. (int_int)
aid1: The ID of the first activity (int)
pid1: The ID of the user who originally submitted the first activity (int)
act1: The first activity (text)
aid2: The ID of the second activity (int)
pid2: The ID of the user who originally submitted the second activity (int)
act2: The second activity (text)
sim: The average human annotated similarity score between act1 and act2 (0-4, 4 indicates very similar)
rel: The average human annotated relatedness score between act1 and act2 (0-4, 4 indicates very related)
ma: The average human annotated motivational alignment score between act1 and act2 (0-4, 4 indicates very similar motivation)
pac: The average human annotated perceived actor congruence between act1 and act2 (-2 - +2, -2 indicates that doing act1 makes it less likely to do act2, 2 indicates that doing act1 makes it more likely to do act2, and 0 means no difference)

There are 1000 annotated pairs of activities in the file.
