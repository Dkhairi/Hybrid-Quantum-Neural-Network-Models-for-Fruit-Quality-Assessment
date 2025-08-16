This codebase implements two hybrid quantum-classical neural network architectures (NNQEv1 and NNQEv2) that integrate parameterized quantum circuits with classical convolutional neural networks.

Key features:

Variational Quantum Circuits (VQCs) with CNOT (NNQEv1) and CZ (NNQEv2) entangling gates.

Integration with TensorFlow and PennyLane/Qiskit.

Training and evaluation on three datasets:

MNIST (public, digits 0–2 subset)

FruitQ (public fruit quality dataset)

Custom Apple Dataset (150 images, released via Zenodo DOI: [insert link])

Benchmarks against classical models (SVM, KNN, CNN) and SOTA deep models (EfficientNetB0, VGG16).\\ these models code are not oncluded as they are availbale open source.

See PLOS Rep1 and PLOS Rep2 

⚙️ Requirements

Python 3.9+

TensorFlow 2.12

PennyLane 0.32

Qiskit >= 1.0.0

Scikit-learn >= 1.3
