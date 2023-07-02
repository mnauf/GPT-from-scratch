Add building blocks one by one to the transformer decoder, and observe the resulting impact with each training.

Train on Shakespeare dataset, followed by training on a subset of OpenWebText. It took 11 hours on a P100 GPU to train a model for 4800 iterations with 512 sequence length, 16 batch size, 6 encoder blocks and 6 multi-head attention layers.