SQL Injection Detection Using Deep Learning(2D CNN):


SQL injection remains one of the most prevalent and dangerous security vulnerabilities in web applications. By exploiting this weakness, attackers can manipulate database queries, leading to unauthorized access, data breaches, and potentially severe financial and reputational damage. Traditional security measures often fail to detect sophisticated SQL injection patterns. Motivated by the need for a more robust and automated solution, this project leverages deep learning to detect SQL injection attempts effectively, thereby enhancing the security posture of web applications.

Project Overview:

This project aims to build a deep learning model using a 2D Convolutional Neural Network (CNN) to classify input queries as either SQL injection attempts or normal user inputs. The project involves several key steps: data collection and preprocessing, model architecture design, training and evaluation, and deployment.
Steps Involved:
1. Data Collection and Preprocessing:

Data Source: The dataset consists of labeled examples of normal user inputs and SQL injection queries.
Preprocessing:
Tokenization: Converting text inputs into sequences of tokens.
Padding: Ensuring all input sequences have a uniform length by padding shorter sequences with zeros.

2. Model Architecture Design:
Architecture:
Embedding Layer: Converts input sequences into dense vectors.
Convolutional Layer: Applies convolutional filters to capture local patterns.
GlobalMaxPooling Layer: Reduces the dimensionality and retains important features.
LSTM Layer: Captures long-range dependencies within the sequences.
Dense Layer: Fully connected layer for final classification.

3. Training and Evaluation:
Training: Train the model using the training data and validate its performance using the test data.
Evaluation: Evaluate the model's accuracy and loss on the test set.

4. Deployment:
Save Model: Save the trained model for future use.
Load Model: Load the model for inference.

Results:
The trained model demonstrated high accuracy in detecting SQL injection attempts, significantly reducing the risk of unauthorized database access and data breaches. This project showcases the potential of deep learning in enhancing web application security.

Future Work:
Model Improvement: Experiment with different architectures, hyperparameters, and preprocessing techniques to further improve detection accuracy.
Real-time Integration: Integrate the model into web application firewalls (WAFs) and intrusion detection systems (IDS) for real-time SQL injection detection.
Adversarial Robustness: Enhance the model's robustness against adversarial attacks and sophisticated evasion techniques.

Repository Structure:
![image](https://github.com/Chhaya-g/Miniproject/assets/117031436/51ff6ebc-8f7f-4456-8799-b03ea60aa3d2)



