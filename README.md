# ANN-sports-image-classification

Sports Image Classifier is a web-based application built with Streamlit and PyTorch that classifies images into various sports categories. Users can upload a sports image, and the app will display the top 3 predicted sports along with confidence scores using a fine-tuned ResNet-50 model.

Core Features:
1. Image Upload and preview
2. Top-3 Predictions with confidence scores and progress bars
3. Test-Time Augmentation (TTA) for more accurate results
4. Custom UI Styling with CSS
5. Device-aware Inference (CPU/GPU)

🧠How It Works:

Frontend: Built with Streamlit + CSS

Backend: PyTorch, ResNet-50, image preprocessing

Prediction Flow:

Upload image

Apply 3 types of TTA

Run model on original + augmented images

Average the probabilities

Display top 3 sports with confidence

| Layer    | Tools Used                  |
| -------- | --------------------------- |
| Frontend | Streamlit, CSS              |
| Backend  | Python, PyTorch             |
| Model    | ResNet-50 (fine-tuned)      |
| Data     | PIL, torchvision.transforms |

🎯Goals and Learning Outcomes:

Deploy a real-time deep learning model using Streamlit

Explore image classification with ResNet

Understand Test-Time Augmentation (TTA) for robust predictions

Practice full-stack ML workflows (preprocessing → inference → UI)

Build deployable ML apps with user interaction

💡Future Scope:

Extend dataset to more sports or activity types

Add Grad-CAM visualizations for explainable AI

Export predictions as PDFs or CSV logs

Deploy on cloud (e.g., Streamlit Cloud, AWS, GCP)

Add model training UI for custom uploads







