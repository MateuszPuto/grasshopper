# Grasshopper architecture

This is a twist on classic Trainsformer architecture. The attention is used to reorder the value query and later compute the convolution over it.

- around 2.25 loss on C4 after 125k training examples (average over 20 last steps)
