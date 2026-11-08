# RNN Student Task: Recurrent Neural Networks from Scratch to PyTorch

A hands-on notebook that builds a Recurrent Neural Network step by step, then compares RNN, LSTM, GRU, CNN and Transformer models on sequence tasks, including MNIST treated as a sequence.

## Contents

| File | Description |
|---|---|
| `koteswara_rao_rnn_student_task.ipynb` | Main notebook covering all 15 tasks |
| `RNN_Dataset.csv` | Generated sequential dataset (5 time steps + binary label) |
| `Student Tasks_rnn.docx` | Task brief |

## Tasks Covered

1. Understand sequence data
2. Generate sequential data
3. Build an RNN architecture from scratch
4. Implement activation functions
5. Forward propagation
6. Trace an RNN manually
7. Implement binary cross-entropy loss
8. Backpropagation Through Time (BPTT)
9. Train the RNN
10. Test the model
11. Compare RNN, LSTM and GRU (including long-sequence memory)
12. MNIST sequence experiment (row-by-row and pixel-by-pixel)
13. Investigate vanishing gradients
14. Experiment with gradient clipping
15. Final comparison report

## Getting Started

```bash
pip install numpy pandas matplotlib scikit-learn torch torchvision
jupyter notebook koteswara_rao_rnn_student_task.ipynb
```

The MNIST dataset is downloaded automatically by `torchvision` into `data/` the first time the notebook runs, so it is not stored in this repository.

## Author

D. Koteswara Rao
