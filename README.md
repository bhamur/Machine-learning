Points to learn here:
test_size=0.2 --> It’s a common rule of thumb: enough test data to get a reliable evaluation, but not so much that you starve the model of training data.
random_state=42 --> train_test_split randomly shuffles the data before splitting.

If you run it twice without setting random_state, you’ll get different splits each time.

By fixing random_state to a number (like 42), you ensure you (and others) always get the same split.
