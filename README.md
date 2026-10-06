# TensorFlow MNIST Neural Network (Raw)

A low-level, manually parameterized two-hidden-layer TensorFlow neural network for MNIST classification.

## Run

Use Python 3.10 with the pinned dependencies:

```bash
python -m pip install -r requirements.txt
python neural_network_raw.py
```

Keras downloads MNIST on first run. The script trains for 3,000 steps, evaluates test accuracy, and plots sample predictions.

## Attribution

The notebook credits Aymeric Damien and the [TensorFlow-Examples project](https://github.com/aymericdamien/TensorFlow-Examples/).