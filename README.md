# Classification of Chest X-Rays

This project explores the application of deep learning techniques for classifying chest X-rays into three categories: **Normal**, **COVID-19**, and **Viral Pneumonia**. The work compares the performance of a baseline Random Forest model with a deep learning model, providing insights into accuracy, recall, and real-world applicability in the healthcare domain.

## Key Features
- **Dataset:** https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database/versions/4 
- **Baseline Model:** Implemented a Random Forest classifier as a benchmark, achieving a test accuracy of 87.5% after grid search optimization.
- **Deep Learning Model:** Developed and optimized a ResNet-50 deep learning model, achieving a test accuracy of 97.1% with superior recall across all classes.
- **Data Preprocessing:** Employed Contrast Limited Adaptive Histogram Equalization (CLAHE) to enhance features in chest X-rays.
- **Model Evaluation:** Conducted grid search on hyperparameters for both models, evaluating performance on a balanced dataset and diverse out-of-the-box samples to test for bias.

## Repository Structure

- **`code/`**: Includes Jupyter notebooks for the implementation of the models, data preprocessing, and analysis.
- **`report/`**: Contains the comprehensive project report detailing methodology, results, and insights.

## Highlights

- **Baseline Results:** The Random Forest model achieved a test accuracy of 87.5%, but suffered from overfitting and limited recall, particularly for COVID-19 and viral pneumonia classifications.
- **Deep Learning Success:** ResNet-50 with three fully connected layers demonstrated superior accuracy and recall, significantly outperforming the Random Forest baseline.
- **Ethical Considerations:** Evaluated model bias using a diverse hand-curated dataset, highlighting the importance of demographic diversity in training data.
- **Efficiency:** ResNet-50 reduced training time while maintaining high accuracy, leveraging GPU-accelerated optimization.

## How to Use

1. Clone the repository:  
   ```bash
   git clone https://github.com/username/classification-of-chest-xrays.git
   ```
2. Navigate to the repository folder:
   ```bash
   cd classification-of-chest-xrays
   ```
3. Explore the code and data folders for implementations and datasets.
4. Open the Jupyter notebook in the `code/` folder to run the Random Forest and ResNet-50 models.
5. Refer to the `report/` folder for a detailed overview of the methodology and results.

## Future Work

- **Expand Dataset:** Incorporate additional diverse data sources to further reduce potential bias.
- **Model Fine-Tuning:** Experiment with advanced architectures and fine-tuning hyperparameters for better generalization.
- **Clinical Testing:** Validate the model on localized hospital data for real-world deployment.

## Acknowledgments

This project was developed as part of the APS360 course at the University of Toronto. Special thanks to the instructors and collaborators for their guidance and support.

---
