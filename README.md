# Network_Intrusion_Detection
Detect network intrusions using ML. Investigate decision tree, KNN, and logistic regression performance on network traffic data. Decision tree outperforms in accuracy, precision, recall, and F1 score.

# Overview:
This project focuses on network intrusion detection using machine learning techniques. The developed model takes inputs such as 'service', 'flag', 'src_bytes', 'dst_bytes', 'count', 'same_srv_rate', 'diff_srv_rate', 'dst_host_srv_count', 'dst_host_same_srv_rate', and 'dst_host_same_src_port_rate' to predict whether an intrusion is likely to occur.

# Features:
<b>Model Building:</b> The project involves building a machine learning model trained on network traffic data to detect potential intrusions.
<br><b>Input Parameters:</b> Users can input various parameters related to network traffic, such as service type, flag, byte counts, and server rates, to predict the likelihood of an intrusion.

# Instructions:
<b>Clone the Repository:</b> Clone this repository to your local machine using Git or download the ZIP file and extract its contents.
<br><b>Install Dependencies:</b> Ensure that you have all the necessary dependencies installed. You can install them using pip:
<br>pip install -r requirements.txt
<br><b>Run the Model:</b> Execute the provided script or notebook to run the machine learning model. Input the required parameters when prompted.
<br><b>View Prediction:</b> Upon execution, the model will predict whether an intrusion is likely to occur based on the input parameters provided.

# Note:
This project serves as a tool for detecting potential network intrusions using machine learning techniques.
<br>Users can input specific network traffic parameters to obtain predictions about the likelihood of intrusions.
<br>Experiment with different input parameters and observe how they affect the model's predictions to gain insights into network security.
