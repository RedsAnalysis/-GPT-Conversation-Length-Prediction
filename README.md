# -GPT-Conversation-Length-Prediction
 GPT Conversation Length Prediction MSR-2024 Challenge

Key Components
Data Collection:
The dataset used for training and testing is stored in the data directory.
Conversations are sourced from various domains, and details about the data structure and sources are explained in the project documentation.

Feature Extraction:
Utilizes GPT-2 transformer features for each conversation.
Extracted features are crucial for understanding the underlying patterns and dynamics in GPT-2-generated content.

Model Training:
Employs a Random Forest Regressor to predict the lengths of conversations.
Training involves using transformer features as input and actual conversation lengths as the target variable.

Evaluation:
Model performance is evaluated using standard regression metrics, including Mean Squared Error (MSE), Mean Absolute Error (MAE), and R-squared.
Visualization tools, such as scatter plots, are used to compare predicted lengths against actual lengths.

Results and Insights:
Summary of the model's performance and insights gained from predictions.
The project aims to provide a deeper understanding of the length variations in GPT-2-generated conversations.
