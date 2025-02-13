# Cover Song Similarity using Dimensional Mapping and Contrastive Loss
The main goal of this project is to design a similarity metric between cover
related songs, given a dataset that consists of cover song cliques. My main
suggestion in the problem was to train a model on labeled pairs (cover related
and non-cover related) using a contrastive loss function to minimize the distance
between similar pairs and maximize the distance between dissimilar pairs. The
method proposed utilizes Dimensionality Reduction, a powerful method that
aims to translate high dimensional data, as the ones in the given Da-Tacos
dataset, to a low dimensional representation such that similar input objects are
mapped to nearby points, and dissimilar inputs are mapped in more distant
points.


