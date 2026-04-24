#  Deep Learning Study Repository

A comprehensive, hands-on learning resource covering deep learning from foundational concepts through modern transformer architectures. Each module is organized as a collection of Jupyter notebooks with theory, code, visualizations, and real-world datasets.

---

##  Repository Structure

### `01_Foundations/`

Core deep learning theory and building blocks.

| Notebook | Topic |
|----------|-------|
| `What_is_DEEP_Learning.ipynb` | Introduction to deep learning |
| `What_is_Activation_Function.ipynb` | Activation functions (Sigmoid, Tanh, ReLU, Leaky ReLU, PReLU, Swish) |
| `BackPropagation.ipynb` | Backpropagation algorithm |
| `Optimizer.ipynb` | Optimization techniques (SGD, Adam, etc.) |
| `Advantages_&_Usages.ipynb` | Advantages and real-world applications of deep learning |

> Includes visual aids: `Sigmoid_Function.png`, `Tanh_Function.png`, `Relu_function.png`, `Leak Relu.png`, `PRelu.png`, `Swish.png`, `Linear_Function.png`

---

### `02_Basic_Term/`

Key training metrics and evaluation terminology.

| Notebook | Topic |
|----------|-------|
| `Accuracy.ipynb` | Understanding accuracy as a metric |
| `Loss.ipynb` | Loss functions and their role in training |
| `Val_Loss_&_Val_Accuracy.ipynb` | Validation loss & accuracy — detecting overfitting |

---

### `03_ANN/`

Artificial Neural Networks — theory and practical prediction tasks.

| Notebook | Topic |
|----------|-------|
| `What_is_ANN.ipynb` | Introduction to ANNs |
| `Why_use_ANN.ipynb` | Motivation and use cases for ANNs |
| `Breast_Cancer.ipynb` | Breast cancer classification |
| `House_pred_1.ipynb` | House price prediction (Dataset 1) |
| `house_Prediction_2.ipynb` | House price prediction (Dataset 2) |
| `Iris_flower_pred.ipynb` | Iris flower species classification |
| `Graduate_prediction.ipynb` | Graduate admission prediction |

**Datasets:** `Admission_Predict.csv`, `breast-cancer.csv`, `Housing_1.csv`, `housing_2.csv`

---

### `04_Training_Techniques/`

Methods to improve training stability and model performance.

| Notebook | Topic |
|----------|-------|
| `batch_normalization.ipynb` | Batch normalization |
| `dropout_regularization.ipynb` | Dropout regularization |
| `gradient_descent_variants.ipynb` | Gradient descent variants (Batch, Mini-batch, Stochastic) |
| `Hyper_Parameter_Tuning.ipynb` | Hyperparameter tuning strategies |

---

### `04_CNN/`

Convolutional Neural Networks — from core concepts to transfer learning.

#### `CNN/` — Core Concepts & Projects

| Notebook | Topic |
|----------|-------|
| `What_is_CNN.ipynb` | Introduction to CNNs |
| `what_is_Convolution_layer.ipynb` | Convolution layers explained |
| `What_padding_&_Strid.ipynb` | Padding and stride |
| `What_is_pooling.ipynb` | Pooling layers |
| `CNN_Architure.ipynb` | CNN architecture overview |
| `Advantage_CNN.ipynb` | Advantages of CNNs |
| `Feature_Extraction.ipynb` | Feature extraction techniques |
| `CNNs_mnist.ipynb` | MNIST digit classification |
| `CNNs_Cat_DOG.ipynb` | Cat vs. Dog image classification |
| `clarf_10.ipynb` | CIFAR-10 image classification |

#### `Data_Augmentation/`

| Notebook | Topic |
|----------|-------|
| `What_is_DataAugmentation.ipynb` | Data augmentation concepts and techniques |

#### `pretrain_CNN_model/` — Transfer Learning

| Notebook | Topic |
|----------|-------|
| `pretrain_model.ipynb` | Introduction to pretrained models |
| `model.ipynb` | Building models with transfer learning |
| `pretain_model_prediction.ipynb` | Inference using pretrained models |

---

### `05_RNN_LSTM_GRU/`

Recurrent neural network families for sequence and time-series modeling.

#### `RNN/` — Vanilla RNN

| Notebook | Topic |
|----------|-------|
| `What_is_RNN.ipynb` | Introduction to RNNs |
| `Type_of_RNN.ipynb` | Types of RNN architectures |
| `RNN_Forward_propagation.ipynb` | Forward propagation in RNNs |
| `Back_propagation.ipynb` | Backpropagation through time (BPTT) |
| `problem_with_RNN.ipynb` | Vanishing/exploding gradient problem |
| `Sequence_prediction.ipynb` | Sequence prediction example |
| `Daily_Min_Tempature.ipynb` | Daily minimum temperature forecasting |
| `AirLine_Passengers.ipynb` | Airline passengers time-series prediction |

#### `LSTM/` — Long Short-Term Memory

| Notebook | Topic |
|----------|-------|
| `What_is_LSTM.ipynb` | Introduction to LSTMs |
| `part_of_LSTM.ipynb` | LSTM gates and internals |
| `Sequence_prediction.ipynb` | Sequence prediction with LSTM |
| `Daily_Min_Tempature.ipynb` | Temperature forecasting with LSTM |
| `Airline_prediction_lstm.ipynb` | Airline passengers prediction with LSTM |

#### `GRU/` — Gated Recurrent Unit

| Notebook | Topic |
|----------|-------|
| `Sequence_prediction.ipynb` | Sequence prediction with GRU |
| `Daily_Min_Tempature.ipynb` | Temperature forecasting with GRU |
| `AirLine_prediction_GRU.ipynb` | Airline passengers prediction with GRU |

**Datasets:** `daily-minimum-temperatures-in-me.csv`, `rnn_sequence_dataset.csv`

---

### `06_Seq2Seq_Model/`

Sequence-to-Sequence models for translation and conversational AI.

| Notebook | Topic |
|----------|-------|
| `What_is_Seq2Seq.ipynb` | Introduction to Seq2Seq models |
| `Why_is_Seq2Seq_important.ipynb` | Importance and applications of Seq2Seq |
| `Encoder_Decoder.ipynb` | Encoder-Decoder architecture |
| `Problem_with_Seq2Seq.ipynb` | Limitations of vanilla Seq2Seq |
| `Tokenization.ipynb` | Tokenization for sequence models |
| `Seq2Seq_fra_eng.ipynb` | French → English machine translation |
| `Cornell_movie_dialog.ipynb` | Conversational model using Cornell Movie Dialogs corpus |

**Datasets:** `fra.txt` (French-English pairs), `cornell movie-dialogs corpus/`

---

### `06_Transformers_Attention/`

Transformer architecture and attention mechanisms — the foundation of modern NLP.

| Notebook | Topic |
|----------|-------|
| `What_is_Transformer.ipynb` | Introduction to the Transformer |
| `Transformer_Architure.ipynb` | Transformer architecture walkthrough |
| `attention_mechanism.ipynb` | Attention mechanism fundamentals |
| `What_is_Self_attentation.ipynb` | Self-attention explained |
| `Why_use_self_attentation.ipynb` | Motivation for self-attention |
| `What_is_Multi-Head_self_attentation.ipynb` | Multi-head self-attention |
| `Masked_Multi_attentation.ipynb` | Masked multi-head attention (decoder) |
| `Cross_Attentation.ipynb` | Cross-attention mechanism |
| `Bahdanau_attentation_mac.ipynb` | Bahdanau (additive) attention |
| `luong_attentation_mac.ipynb` | Luong (multiplicative) attention |
| `What_is_positional_Encodding.ipynb` | Positional encoding |
| `bert_fine_tuning.ipynb` | BERT fine-tuning |

> Includes visual aids: `Transformer_Architure.png`, `Attention_mechanism.png`, `Self_Attentation.jfif`, `Maked Multihead self Attenattion.png`, `Corss Attentation.png`

---

##  Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/Dev-with-Mouzan/Deep-Learning.git
   cd Deep-Learning
   ```

2. **Install dependencies**
   ```bash
   pip install tensorflow torch numpy scikit-learn pandas matplotlib num2words
   ```

3. **Open any notebook** and execute cells sequentially to follow the explanations and code.

---

## Dependencies

| Library | Purpose |
|---------|---------|
| `tensorflow` | Neural network training and modeling |
| `torch` | PyTorch-based model implementations |
| `numpy` | Numerical computing |
| `scikit-learn` | Data preprocessing and evaluation metrics |
| `pandas` | Data loading and manipulation |
| `matplotlib` | Plotting and visualization |
| `num2words` | Number-to-word conversion utilities |

---

##  Notes

- This repository is intended for **learning and experimentation**, not production use.
- Notebooks demonstrate concepts visually with small-scale, easy-to-follow examples.
- Datasets are included in their respective folders for immediate hands-on use.
- Feel free to extend any section with additional experiments or model variations.

---

##  Contributing

Contributions are welcome! To add a new topic or improve an existing notebook:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-topic`)
3. Commit your changes (`git commit -m "Add new topic notebook"`)
4. Push to the branch (`git push origin feature/new-topic`)
5. Open a Pull Request

---

##  Contact

For questions, suggestions, or collaboration — open an issue or reach out via the repository's discussion tab.