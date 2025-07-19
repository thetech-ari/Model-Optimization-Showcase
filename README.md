# Model Optimization Showcase

This project demonstrates how to train a basic PyTorch neural network and then apply various optimization techniques to reduce its size and improve inference efficiency.

## Objectives

- Train a baseline image classifier using PyTorch
- Apply **pruning** to remove unnecessary weights
- Apply **quantization** to reduce model size and latency
- Compare performance metrics (accuracy, size, inference speed)

## Techniques Used

- PyTorch & TorchVision
- Pruning (using `torch.nn.utils.prune`)
- Post-training Quantization
- Matplotlib for visualization

## Structure

| Notebook | Description |
|----------|-------------|
| `1_train_baseline_model.ipynb` | Train original model |
| `2_model_pruning.ipynb` | Apply and evaluate pruning |
| `3_model_quantization.ipynb` | Apply and evaluate quantization |

## How to Run

```bash
git clone https://github.com/thetech-ari/model-optimization-showcase.git
cd model-optimization-showcase
pip install -r requirements.txt
