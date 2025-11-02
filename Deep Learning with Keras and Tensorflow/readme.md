# Deep Learning with Keras & TensorFlow  
**Repository:** [IBM_AI / Deep Learning with Keras and TensorFlow](https://github.com/thesyzling/IBM_AI/tree/main/Deep%20Learning%20with%20Keras%20and%20Tensorflow)  
**Based on the course:** Deep Learning with Keras and TensorFlow (IBM via Coursera)  

## 🚀 Overview  
This repository contains practical implementations, notebook experiments and project work aligned with the “Deep Learning with Keras & TensorFlow” course. The course covers advanced deep-learning topics using Keras (as part of TensorFlow 2.x) and helps you build, train and optimise neural networks for a variety of tasks (CNNs, Transformers, Unsupervised learning, RL).  

This code base is intended both as a **learning companion** (to follow the concepts from the course) and as a **reference library** for real-world experimentation.

## 📚 Course Modules & Key Topics  
Here’s a summary of what the course covers (and thus what this repository touches on):  
| Module | Key Topics |  
|--------|------------|  
| 1. Advanced Keras Functionalities | Functional API, model subclassing, custom layers, integration with TensorFlow 2.x.|  
| 2. Advanced CNNs in Keras | Convolutional architectures, data augmentation, transfer learning, pre-trained models, image processing.|  
| 3. Transformers in Keras | Building Transformers for sequential & time-series data, text generation, TensorFlow for sequential data.|  
| 4. Unsupervised Learning & Generative Models | Autoencoders, diffusion models, GANs, unsupervised model design in Keras/TensorFlow.|  
| 5. Advanced Keras Techniques | Custom training loops, hyperparameter tuning (Keras Tuner), model optimisation.|  
| 6. Introduction to Reinforcement Learning with Keras | Q-learning, Deep Q-Networks (DQNs), reinforcement learning workflows in Keras.|  
| 7. Final Project & Assignment | Apply the learned techniques: classification model using transfer learning.|  

## 🗂 Repository Structure  
Deep Learning with Keras and TensorFlow/
│
├── module1_advanced_keras/ ← Notebooks + code for Module 1
├── module2_cnn_transfer/ ← Module 2: CNNs + Transfer Learning
├── module3_transformers/ ← Module 3: Transformer models
├── module4_unsupervised_generative/ ← Module 4: Autoencoders, GANs etc
├── module5_training_loops_opt/ ← Module 5: Custom loops, hyperparam tuning
├── module6_reinforcement_learning/ ← Module 6: Q-learning, DQNs
├── final_project/ ← Module 7: Final capstone project code + report
└── README.md ← This file

bash
Kodu kopyala

> Note: You may adjust folder names, split further etc. to reflect how you organised your work.

## 🔧 Setup & Usage  
To run experiments in this repo, follow these steps:

1. Clone this repository:  
   ```bash
   git clone https://github.com/thesyzling/IBM_AI.git
   cd "Deep Learning with Keras and TensorFlow"
(Recommended) Create a virtual environment and install dependencies:

bash
Kodu kopyala
python3 -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
pip install -r requirements.txt
Launch a Jupyter notebook (or your preferred IDE) and open the desired module folder, e.g. module2_cnn_transfer/notebook.ipynb.

Run the code cells step-by-step, adapt to your own dataset or parameters if desired.

To reproduce the final-project results, follow the instructions inside final_project/README_project.md (or similar file).

📈 What You Will Learn / Skills Gained
By working through this repository (in parallel with the course) you will build skills in:

Designing custom neural network architectures with Keras Functional API and subclasses.

Training state-of-the-art convolutional neural networks and applying transfer learning to image tasks.

Building Transformer models for sequential and time-series prediction, text generation.

Applying unsupervised deep-learning techniques: autoencoders, GANs, diffusion models.

Writing custom training loops, tuning hyperparameters, optimising models using TensorFlow & Keras.

Implementing reinforcement-learning workflows (Q-Learning, Deep Q-Networks) in Keras.

Integrating research-level deep-learning concepts into real project code, from dataset preparation to model deployment.

🎯 Why This Matters
Deep learning is transforming many fields — computer vision, natural language processing, time-series forecasting, robotics, autonomous systems. The course emphasises that mastering Keras (together with TensorFlow) enables you to build production-ready deep-learning systems. 
Coursera

This repository adds value by converting those learnings into reproducible code, a personal project library, and a portfolio component you can showcase to employers or collaborators.
