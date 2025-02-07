# RLHF-BMF
RLHF-BMF is an iterative model comprising a chain of RLHF model annotators, with RLHF models annotating each other in a chain, culminating in a final RLHF model annotated by a human.

## Core Hypothesis:
In a chain of RLHF models, where each model is trained on annotations provided by the previous model, the bias introduced by the initial human annotator will decrease over successive iterations. This will be reflected in improved bias metrics and balanced output characteristics, without significant degradation in overall model performance.
