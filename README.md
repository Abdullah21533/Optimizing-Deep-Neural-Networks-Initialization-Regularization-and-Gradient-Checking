# Optimizing-Deep-Neural-Networks-Initialization-Regularization-and-Gradient-Checking
This repository implements essential deep learning optimization techniques, focusing on:

- ✅ **Weight Initialization**
  - Zeros Initialization
  - Random (Large) Initialization
  - He Initialization

- ✅ **Regularization**
  - L2 Regularization
  - Dropout Regularization

- ✅ **Gradient Checking**
  - 1D Gradient Checking
  - N-Dimensional Gradient Checking

These implementations are based on neural networks using NumPy and cover:
- Improving convergence speed during training
- Preventing overfitting on small or noisy datasets
- Verifying the correctness of your backpropagation implementation

---

## 📁 Folder Structure

.
├── initialization/
│ ├── initialize_parameters_zeros.py
│ ├── initialize_parameters_random.py
│ └── initialize_parameters_he.py
│
├── regularization/
│ ├── compute_cost_with_regularization.py
│ ├── backward_propagation_with_regularization.py
│ └── dropout_forward_backward.py
│
├── gradient_checking/
│ ├── gradient_check_1D.py
│ └── gradient_check_nD.py
│
├── utils/
│ ├── init_utils.py
│ ├── reg_utils.py
│ └── gc_utils.py
│
├── testCases/
│ └── testCases.py
│
└── README.md
