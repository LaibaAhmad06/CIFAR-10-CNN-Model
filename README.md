🚀 CIFAR-10 Image Classification using Custom CNN

We recently developed a Convolutional Neural Network (CNN) from scratch to classify images from the CIFAR-10 dataset, focusing on understanding the impact of optimization and regularization techniques rather than just achieving high accuracy.

🔍 Key Highlights:
Designed and implemented a custom CNN architecture (MyCNN) along with a dropout-based variant.
Conducted comparative experiments on:
Optimization techniques: Adam vs SGD (SGD achieved better performance ~78.8% accuracy).
Regularization: Evaluated dropout impact, observing trade-offs between overfitting and performance.
Built a complete ML pipeline including:
Data preprocessing
Model training & evaluation
Confusion matrix & per-class performance metrics
Training curve visualization

📊 Results & Insights:
Achieved ~79.7% test accuracy with the baseline model.
Found that SGD outperformed Adam for this architecture.
Observed that dropout requires careful tuning and longer training to be effective.

💡 Key Takeaway:
This project strengthened our understanding of how architectural choices, optimization strategies, and regularization techniques influence deep learning model performance.
