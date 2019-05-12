# Learning-With-Messy-Labels

We try to learn segmentation from a messy input where all boundries are scattered. We first train on the entire trainset. We then identify hard samples from the train and validation set that the model did poorly on and train another model to see how transferable the learnings from hard samples in the train set are to the validation set.
