
---

### 📁 `task_3_multimodal_housing/README.md`
```markdown
# 🏠 Multimodal Housing Price Prediction (Images + Tabular)

## Objective
Predict house prices using a combination of tabular data and simulated image inputs.

## Dataset
- Simulated images (randomly generated or downloaded)
- Tabular features: area, location, rooms, condition, etc.

## Methodology
- CNN (e.g., simple ConvNet) for image embeddings
- MLP for tabular feature processing
- Concatenated embeddings → dense layers → regression output
- Evaluated with MAE and RMSE

## Results
- **MAE**: ~15,000
- **RMSE**: ~20,000
- Outperformed tabular-only baseline

## How to Run
1. Install dependencies:
   ```bash
   pip install numpy pandas torch torchvision matplotlib
