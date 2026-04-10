# Deep Learning

A comprehensive collection of deep learning implementations and tutorials covering neural network architectures, natural language processing, and time series analysis. This repository contains practical Jupyter notebooks demonstrating core concepts with working code examples.

## Repository Contents

### Neural Network Fundamentals

#### Convolutional Neural Networks (CNN)
Located in the `CNN/` directory:

| Notebook | Description |
|----------|-------------|
| `0. Introduction_of_CNN.ipynb` | Theoretical foundations of convolutional neural networks |
| `1. CNN.ipynb` | Building CNN architectures from scratch |
| `2. CNN_Classification.ipynb` | Image classification using CNNs |
| `Cat_vs_Dog_Classification.ipynb` | Binary classification on the cats vs dogs dataset |
| `cnn.ipynb` | Additional CNN implementations |
| `Data Augmentation Preprocessing.ipynb` | Image augmentation techniques for training |

**Reference Material**: `Deep_Learning_ANN_CNN_RNN_Detailed.pdf` - Comprehensive guide covering Artificial Neural Networks, Convolutional Neural Networks, and Recurrent Neural Networks.

### Recurrent Neural Networks (RNN)
| Notebook | Description |
|----------|-------------|
| `rnn (1).ipynb` | Implementation of recurrent neural networks for sequence modeling |

### Autoencoders
| Notebook | Description |
|----------|-------------|
| `autoencoding.ipynb` | Building autoencoders for dimensionality reduction and feature learning |
| `Auto prediction (1).ipynb` | Predictive modeling using autoencoder architectures |

### Natural Language Processing (NLP)
| Notebook | Description |
|----------|-------------|
| `basic for natural language process.ipynb` | Introduction to NLP concepts and techniques |

**Reference Material**: `Basics_of_Natural_Language_Processing_NLP (1) (1).pdf` - Foundational NLP concepts and applications.

### Time Series Analysis
| Notebook | Description |
|----------|-------------|
| `time series analysis.ipynb` | Techniques for analyzing and forecasting time series data |

## Topics Covered

### Convolutional Neural Networks
- Convolution operations and feature extraction
- Pooling layers and spatial dimension reduction
- CNN architectures for image classification
- Data augmentation strategies
- Transfer learning concepts

### Recurrent Neural Networks
- Sequential data processing
- Hidden state propagation
- Vanishing gradient problem
- LSTM and GRU cells

### Autoencoders
- Encoder-decoder architecture
- Latent space representation
- Dimensionality reduction
- Anomaly detection applications

### Natural Language Processing
- Text preprocessing and tokenization
- Word embeddings
- Sequence-to-sequence models
- Sentiment analysis

### Time Series
- Trend and seasonality decomposition
- Forecasting techniques
- Feature engineering for temporal data

## Technical Requirements

### Dependencies
- Python 3.8+
- TensorFlow or PyTorch
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Jupyter Notebook

### Installation

```bash
# Clone the repository
git clone https://github.com/krish2248/Deep-Learning.git
cd Deep-Learning

# Install dependencies
pip install tensorflow numpy pandas matplotlib scikit-learn jupyter

# Launch Jupyter
jupyter notebook
```

## Learning Path

### Recommended Order

1. **Start with CNNs**: Begin with `0. Introduction_of_CNN.ipynb` to understand convolutional operations
2. **Build Networks**: Progress through `1. CNN.ipynb` and `2. CNN_Classification.ipynb`
3. **Apply to Real Data**: Work on `Cat_vs_Dog_Classification.ipynb` for practical experience
4. **Learn Data Augmentation**: Study `Data Augmentation Preprocessing.ipynb`
5. **Explore RNNs**: Move to `rnn (1).ipynb` for sequence modeling
6. **Understand Autoencoders**: Complete the autoencoding notebooks
7. **NLP Fundamentals**: Finish with NLP and time series notebooks

## Dataset Information

### Cat vs Dog Classification
The binary classification project uses a subset of the Kaggle Dogs vs Cats dataset:
- Training images of cats and dogs
- Binary labels (0: cat, 1: dog)
- Data augmentation applied during training

## Project Applications

The techniques in this repository can be applied to:

- **Computer Vision**: Image classification, object detection, image segmentation
- **Natural Language**: Sentiment analysis, text classification, named entity recognition
- **Time Series**: Stock price prediction, weather forecasting, demand planning
- **Generative Models**: Image generation, data augmentation, anomaly detection

## Reference Materials

Two PDF documents are included for theoretical background:

1. **Deep_Learning_ANN_CNN_RNN_Detailed.pdf**
   - Artificial Neural Network fundamentals
   - CNN architecture details
   - RNN and sequence modeling

2. **Basics_of_Natural_Language_Processing_NLP.pdf**
   - NLP pipeline overview
   - Text preprocessing techniques
   - Common NLP applications

## Further Reading

- [Deep Learning Book by Goodfellow, Bengio, and Courville](https://www.deeplearningbook.org/)
- [Stanford CS231n: Convolutional Neural Networks](http://cs231n.stanford.edu/)
- [Stanford CS224n: NLP with Deep Learning](http://web.stanford.edu/class/cs224n/)

## Contributing

Contributions are welcome. Please open an issue or submit a pull request for:
- Bug fixes in existing notebooks
- Additional deep learning implementations
- Documentation improvements

## License

MIT License
