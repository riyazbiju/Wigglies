**Wigglies Classification using Neural Networks**

This code contains a comprehensive implementation of two neural network architectures for classifying 'wigglies' data using PyTorch.

**Overview**

The implementation demonstrates advanced neural network techniques for multi-class classification with:
 * Multi-Layer Perceptron (MLP) - Fully connected feed-forward network
 * Convolutional Neural Network (CNN) - Spatial pattern recognition architecture
 * Comprehensive data preprocessing and normalization
 * Model comparison and evaluation metrics
 * GPU/CPU acceleration support

**Prerequisites**

Install the required Python libraries:

```bash
pip install torch torchvision numpy matplotlib scikit-learn seaborn pandas tqdm
```

**File Structure**

* `Portfolio_Wigglies.ipynb` - Contains the complete, commented source code for both neural network implementations
* `trainset.pth` - Training dataset with labeled samples
* `testset_noLabels.pth` - Test dataset for final predictions
* `submission.csv` - Generated predictions for test set

**Key Components**

1. **Data Loading and Preprocessing**
2. **MLP Model Architecture**
3. **CNN Model Architecture**
4. **Training Pipeline**
5. **Model Evaluation**
6. **Final Predictions and Comparison Plots**
**Acknowledgment**

Thanks to Prof. Dr. Magda Gregorova for providing insightful lectures on Deep Learning and giving us these interesting and fun assignments.
