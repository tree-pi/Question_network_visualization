Few shot learning of actions from video clips.

What is the training data?
	_a_ clips of actions
What is the goal?
	_a_ few/zero shot learning for new actions (e.g. "take-mushroom-out")
What is the model?

	_ What is the representation form?
		_a_ embedding.
	_ How to train?
		_a_ weakly supervised learning: loss function on the embeddings (word only; word + video; or something joint between word + video)
	_ What is the loss?
		_a_ triplet loss (Which assumes just things in the same class should be closer)

