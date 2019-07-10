# Learning-With-Messy-Labels
----OUTDATED---- New approach using distance maps will be uploaded

We try to learn segmentation from a messy input where all boundries are scattered. We first train on the entire trainset. We then identify hard samples from the train that the model did poorly on and train another model to see how transferable the learnings from hard samples in the train set to a shortned validation set.
