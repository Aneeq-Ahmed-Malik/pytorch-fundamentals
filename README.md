# PyTorch Fundamentals

A comprehensive guide to PyTorch fundamentals, covering essential concepts from basic tensor operations to building neural networks. This repository serves as a practical reference for learning PyTorch's core components.

## Contents

### 1. Tensor Operations
- Basic tensor creation and manipulation
- Shape operations and broadcasting
- `torch.stack` vs `torch.cat`
- `torch.unsqueeze` for dimension manipulation

### 2. Automatic Differentiation
- Gradient computation with autograd
- Understanding `requires_grad` and `backward()`
- Working with computation graphs
- Jacobian derivatives and Vector-Jacobian Products (VJP)

### 3. Neural Network Building Blocks
- `nn.Module` architecture
- Defining forward passes
- Activation functions (functional vs module style)
- Using `nn.Sequential` for simple architectures

### 4. Loss Functions and Optimization
- Common loss functions (MSE, CrossEntropy)
- Understanding optimizers (SGD, Adam, RMSprop)
- Parameter updates and gradient management
- Visualization of computation graphs

### 5. Data Handling
- PyTorch Dataset classes
- Custom dataset implementation
- DataLoader for batching and shuffling
- Working with MNIST dataset

## Prerequisites
```bash
pip install torch torchvision torchviz
```

For visualization features, you may also need:
```bash
pip install graphviz
```

## Usage

The notebook is designed to be run sequentially. Each section builds upon previous concepts:

1. Start with basic tensor operations to understand PyTorch's data structures
2. Progress through gradient computation to understand backpropagation
3. Learn to build and train neural networks
4. Understand data loading and preprocessing

## Key Concepts Covered

- **Autograd System**: How PyTorch tracks operations and computes gradients automatically
- **Computation Graphs**: Visual representation of forward and backward passes
- **Model Architecture**: Proper structuring of neural network components
- **Training Loop**: Complete workflow from data loading to parameter updates

## Notes

- All examples include detailed explanations and mathematical formulations where applicable
- Code includes inline comments for clarity
- Computation graph visualizations help understand gradient flow

## Future Additions

This repository will be expanded with:
- Advanced architectures with pytorch

## Structure
```
pytorch-fundamentals/
├── README.md
├── pytorch.ipynb          # Main tutorial notebook
└── requirements.txt       # Python dependencies
```

## License

MIT License - Feel free to use this material for learning purposes.

## Acknowledgments

Based on official PyTorch documentation and best practices from the deep learning community.
```

## requirements.txt

torch>=2.0.0
torchvision>=0.15.0
torchviz>=0.0.3
graphviz>=0.21
jupyter>=1.0.0
matplotlib>=3.5.0
```
