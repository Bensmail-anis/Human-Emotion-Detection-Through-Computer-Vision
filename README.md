### **Human Emotion Detection Repository**

\======================================

This repository is structured to provide a comprehensive overview of our Human Emotion Detection project, including data preparation, model architectures, training details, and performance analysis. Below is a detailed explanation of the repository structure:

### **Repository Structure**

#### **1\. data/**

Contains all datasets in TFRecord format, organized into three categories:

*   **raw/**: Original dataset without any augmentations.
    
*   **augmented/training/**: Dataset with standard augmentations applied.
    
*   **cut\_mix\_augmented/training/**: Dataset with CutMix augmentation, enhancing data diversity.
    

#### **2\. models/**

Stores training history, architectural details, and metrics for each model used in the project:

*   **EfficientNetB4/**: Files related to the EfficientNetB4 architecture, including updates and fine-tuning details.
    
*   **EfficientNetB4\_finetuned/**: Files and performance metrics for the fine-tuned EfficientNetB4 architecture.
    
*   **LeNet-5/**: Contains files for the LeNet-5 model and its performance metrics.
    
*   **ResNet-34/**: Includes files and results for the ResNet-34 model.
    

#### **3\. notebooks/**

Detailed and well-documented Jupyter notebooks that explain each step of the project and experiments:

*   **Human\_Emotion\_Detection\_through\_Computer\_Vision\_ComprehensiveGuide.ipynb**: A comprehensive guide to the entire project, including methodology and key insights.
    
*   **Human\_Emotion\_Detection\_using\_EfficientNetB4\_fine\_tuning.ipynb**: Notebook detailing the fine-tuning process for the EfficientNetB4 model.
    
*   **Human\_Emotion\_Detection\_using\_ResNet\_Architecture.ipynb**: Details the use of the ResNet architecture for emotion detection.
    
*   **Human\_Emotion\_Detection\_using\_Transfer\_Learning\_with\_EfficientNetB4.ipynb**: Explains the transfer learning approach using EfficientNetB4.

*   **Exploring VGG16/ EfficientNetB5/EfficientNetB4 for Human Emotion Detection with Grad-CAM Visualization.ipynb** : For intermediate layers visualizations , Grad-CAM method , additional training for VGG16 and EfficientNetB5 
    

#### **4\. results/**

Contains visualizations, metrics, and performance summaries for each model:

*   **EfficientNetB4/**: Visualizations and metrics for the EfficientNetB4 model.
    
*   **EfficientNetB4\_finetuned/**: Results and visualizations for the fine-tuned EfficientNetB4 model.
    
*   **LeNet-5/**: Performance analysis and metrics for the LeNet-5 model.
    
*   **ResNet-34/**: Results and visualizations for the ResNet-34 model.
    

#### **5\. utils/images/**

Auxiliary folder containing images used throughout the project, such as architecture diagrams and result visualizations.

### **Releases**

Each model version has been packaged as a release, including detailed explanations and usage instructions.

### **Usage Instructions**

1.  Navigate to the relevant folder to access data, models, or notebooks.
    
2.  Refer to the notebooks for detailed step-by-step explanations and implementation details.
    
3.  Explore the results/ folder for performance metrics and visualizations.
    

This structure ensures clarity and ease of navigation for researchers and developers working on the Human Emotion Detection task.
