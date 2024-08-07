# KHCR
Title: Developing a CNN-DenseNet-Based Deep Learning Approach for Kannada Handwritten Character Recognition System

Authors and Affiliations:

Sachin R Totad, Dept. of AI & ML, Ramaiah Institute of Technology, Bangalore, India. Email: sachinrt0912@gmail.com
Naveen Kumar HG, Dept. of AI & ML, Ramaiah Institute of Technology, Bangalore, India. Email: navkumar9876@gmail.com
Nivedith Inagandla, Dept. of AI & ML, Ramaiah Institute of Technology, Bangalore, India. Email: inagandlanivedith@gmail.com
Nallamalli V Venkata Satya Sai Yaswanth, Dept. of AI & ML, Ramaiah Institute of Technology, Bangalore, India. Email: nallamalliyaswanth@gmail.com
Megha J, Assistant Professor, Dept. of AI & ML, Ramaiah Institute of Technology, Bangalore, India. Email: meghaj@msrit.edu
Abstract:
The creation of a system that can recognize handwritten characters in Kannada, a language from the Dravidian family, using Convolutional Neural Networks (CNNs) and DenseNet structures, aims to overcome the complexities of the Kannada script. Kannada, known for its diverse characters and complex strokes, often results in errors when traditional recognition methods are used. This project seeks to improve the precision and dependability of recognizing Kannada handwritten characters by using CNNs for extracting features and DenseNet's effective feature reuse. It involves building a detailed dataset, training and refining a CNN-DenseNet model, and creating an easy-to-use interface for real-world use. The research process includes careful gathering and preparation of data to ensure a strong training set. The deep learning model, which combines CNNs and DenseNet, tackles the script's intricacies by solving problems related to vanishing gradients and enhancing the flow of information between layers. Thorough testing and continuous improvement guarantee high performance and accuracy. The results of this project represent a significant step forward in recognizing handwritten Kannada characters, setting the stage for further developments and applications in areas like educational resources, document digitization, and archival systems.

Keywords:
CNN, DenseNet, CHARS74K, Deep Learning, Transfer Learning

I. Introduction:
The Kannada Handwritten Character Recognition System is designed to digitize Kannada characters using a deep learning approach, specifically focusing on Convolutional Neural Networks (CNN) and DenseNet architectures. This system aims to handle the complexities of Kannada script, including curved strokes and Ottaksharas, providing a robust solution for digital access to Kannada literature and information. The use of CNNs for feature extraction, combined with DenseNet's efficient feature reuse capabilities, addresses the challenges posed by the intricate nature of Kannada characters.

Contributions:
The hybrid approach combining Convolutional Neural Networks (CNN) and DenseNet architectures for Kannada Handwritten Character Recognition. By leveraging CNN for robust feature extraction and DenseNet for efficient feature reuse, our system achieves enhanced accuracy in recognizing handwritten Kannada characters. Trained on the CHAR74K. The model not only improves character recognition but also supports educational tools, document digitization, and archival systems.

Methodology:
The methodology begins with the collection of a diverse dataset encompassing various writing styles, qualities, and conditions of handwritten Kannada characters. Preprocessing steps include normalization, binarization, and noise reduction to standardize input data quality and enhance image clarity. Feature extraction focuses on extracting key visual attributes directly from preprocessed images using techniques such as edge detection and texture analysis. Data augmentation techniques such as rotation, scaling, translation, and synthetic noise injection are integrated into the training pipeline. Advanced neural network architectures including CNNs and DenseNets are implemented. Techniques such as transfer learning, fine-tuning, and regularization are employed to optimize model performance and mitigate overfitting. Hyperparameter tuning using methods like grid search and cross-validation ensures optimal configuration of network parameters. Evaluation of our models shows promising results, with the CNN achieving 86% accuracy and the DenseNet surpassing with 91%.

Conclusion:
The CNN model achieved an accuracy of 86%, while the DenseNet model surpassed it with an accuracy of 91% in recognizing Kannada handwritten characters. Leveraging advanced architectures like CNNs and DenseNets enabled robust feature extraction and efficient gradient propagation, crucial for enhancing recognition accuracy. The developed system facilitates the seamless translation of handwritten Kannada characters into digital text formats, supporting cultural preservation and document digitization efforts. Future directions include further optimization through ensemble techniques and fine-tuning model parameters, which could potentially enhance accuracy and scalability, paving the way for broader applications in linguistic research and archival digitization.
