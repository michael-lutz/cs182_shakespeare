# Shakespeare Playground

This repository contains code for training a character-level language model to generate Shakespearean text.

## Training

To train the model, run the following command:

```bash
python -m train.py <flags>
```

The flags are specified in the `Config` class in `train.py`. This will load a
xax task and launch a training & validation loop. Logging should automatically
be visible in `localhost:9249`, but you can run the following command to view
the logs in a more convenient format:

```bash
tensorboard --logdir=<path-to-logs>
```

All models have been tested to produce reasonable results from the prompt "To
be" and most reach ~1.0 training loss.

# Example Generations
The following was generated by an SSM with a diagonal A matrix.
```
So louds for his marks, and the people,
Unto tames, at my lord, is my treasons,
Pub one of aloud; and satisfairing,
And out of myself ambidenelies; and their child!
O you mayst bakess. In vain! so he maiden--
Their own another soldiers, which is in it
Untolen years you rose. What is these same
How whom I treak our kind o'er 'man's face,
And, then, but tedious love me manife
That accordiment be to 's head; little-hinded it a
any thing but you have we disdain will pluck.
```

