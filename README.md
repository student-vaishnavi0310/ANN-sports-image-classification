# ANN-sports-image-classification

Sports Image Classifier is a web-based application built with Streamlit and PyTorch that classifies images into various sports categories. Users can upload a sports image, and the app will display the top 3 predicted sports along with confidence scores using a fine-tuned ResNet-50 model.
Core Features:
1. Image Upload and preview
2. Top-3 Predictions with confidence scores and progress bars
3. Test-Time Augmentation (TTA) for more accurate results
4. Custom UI Styling with CSS
5. Device-aware Inference (CPU/GPU)

How It Works:
Frontend: Built with Streamlit + CSS
Backend: PyTorch, ResNet-50, image preprocessing
Prediction Flow: Upload → Augment → Predict → Display top-3 classes

| Layer    | Tools Used                  |
| -------- | --------------------------- |
| Frontend | Streamlit, CSS              |
| Backend  | Python, PyTorch             |
| Model    | ResNet-50 (fine-tuned)      |
| Data     | PIL, torchvision.transforms |

Learning Outcomes:
Build and deploy a deep learning classifier
Use TTA for improved model inference
Develop a full-stack AI app with user interaction

