## Title of the Project
Parkinson's prediction using deep learning

## About
What is Parkinson’s Disease?
Parkinson's disease (PD), or simply Parkinson's is a long-term degenerative disorder of the central nervous system that mainly affects the motor system. The symptoms usually emerge slowly and, as the disease worsens, non-motor symptoms become more common. The most obvious early symptoms are tremor, rigidity, slowness of movement, and difficulty with walking,but cognitive and behavioral problems may also occur. Parkinson's disease dementia becomes common in the advanced stages of the disease. Depression and anxiety are also common, occurring in more than a third of people with PD. Other symptoms include sensory, sleep, and emotional problems. The main motor symptoms are collectively called "parkinsonism", or a "parkinsonian syndrome.

## Features
- Implements advance neural network method.

  Utilizes deep learning models such as Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), or Long Short-Term Memory (LSTM) networks to analyze features for detecting Parkinson’s disease.

- A framework based application for deployment purpose.

  The model can be deployed using popular frameworks like TensorFlow, PyTorch, or Keras, with options to deploy in a cloud-based platform or as a standalone application.
  
- High scalability.

  The system is scalable to handle a growing number of patient records and can be extended to include   additional features like gait analysis or voice processing.
  
- Less time complexity.

   Optimized models using techniques like transfer learning, hyperparameter tuning, and early stopping to ensure faster training and inference times.
   
- A specific scope of Chatbot response model, using json data format.

   The project could include a chatbot that interacts with patients or clinicians, offering predictions and explanations. The chatbot will use JSON data to communicate between the model and the user interface for integration into clinical tools.
   

## Requirements
Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks and GPU acceleration.

Development Environment: Python 3.6 or later is necessary for coding the Parkinson’s disease detection system, particularly for managing libraries and frameworks used in deep learning.

Deep Learning Frameworks:

    TensorFlow or PyTorch for training the deep learning models to predict Parkinson’s disease.
    Optional: Keras as a high-level API for TensorFlow.

Data Processing Libraries:

    NumPy for handling and processing large numerical datasets.
    Pandas for data manipulation and preprocessing.
    SciPy for scientific computations and statistical operations.

Machine Learning Libraries:

    scikit-learn for data splitting, feature scaling, and evaluation metrics.
    XGBoost (optional) for hybrid deep learning and traditional machine learning approaches.

Audio/Voice Processing Libraries (if applicable):

    librosa for audio feature extraction (such as if voice data is used for detecting vocal symptoms of Parkinson’s).

Image Processing Libraries (if applicable)**:

    OpenCV for handling visual input (e.g., gait analysis).

Version Control:

    Git for collaborative development, version control, and management of codebase.

Integrated Development Environment (IDE):

    VSCode or PyCharm as the IDE for writing, debugging, and testing the code.

Additional Dependencies:

    TensorFlow GPU for hardware acceleration.
    Matplotlib and Seaborn for data visualization.
    Jupyter Notebook for interactive code development and prototyping.

## System Architecture

![dataset](https://github.com/user-attachments/assets/08efd6c5-8eb3-4c3f-930d-f8380caeb7fa)


## Output
![accuracy](https://github.com/user-attachments/assets/3f57e06c-b510-47a6-9c7f-7536404da384)

#### Output1 - Name of the output
WAVE HEALTHY
![wave-healthy](https://github.com/user-attachments/assets/fdb05712-14a4-4f97-a3ed-63e663caa599)


#### Output2 - Name of the output
WAVW PARKINSON
![wave-parkinson](https://github.com/user-attachments/assets/16546407-ae6b-41b3-b83d-8ff565324209)

Detection Accuracy: 95.6%



## Results and Impact
Results:
  The Parkinson Disease Detection System provides an efficient, non-invasive tool for early diagnosis, potentially improving patient outcomes by allowing timely intervention. By leveraging deep learning, the model is capable of analyzing complex patterns in patient data (such as vocal features, gait, or handwriting analysis), making it more accurate than traditional diagnostic methods.The project demonstrates how deep learning can significantly enhance medical diagnostics by automating complex tasks, reducing human error, and improving detection speed. This system could be integrated into clinical workflows, assisting healthcare professionals in detecting Parkinson’s disease with greater precision and reducing diagnostic delay.
  
Impact:
   Improved Early Detection: Earlier diagnosis of Parkinson's disease can lead to better patient management, slowing disease progression with appropriate treatment and improving quality of life.
Scalable and Cost-Effective: The system offers a scalable solution that can be widely deployed, making it accessible to healthcare providers worldwide, particularly in remote or resource-limited settings.
Promotes AI in Healthcare: This project contributes to the ongoing advancement of AI and deep learning in healthcare, showcasing how such technologies can complement clinical expertise.


  

## Articles published / References
1.Prabhavathi, K., Patil, S. (2022). “Tremors and Bradykinesia. In: Arjunan, S.P., Kumar, D.K. (eds) Techniques for Assessment of Parkinsonism for Diagnosis and Rehabilitation”.

2.Nicoló G. Pozzi, Ioannis U. Isaias (2022), “Chapter 19 - Adaptive deep brain stimulation: Retuning Parkinson's disease”



