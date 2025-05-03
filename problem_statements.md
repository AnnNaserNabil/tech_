
• A dump dataset (unstructured or semi-structured data)
• A topic list (for context on features/labels)
Your task will be split into three parts:
Step 1: Build a Basic Model
• Prepare the dataset manually: clean, structure, and split into features (X) and labels
(y) as required.
• Write a Python script to:
o Preprocess the data
o Train a machine learning model on the prepared dataset
o Predict outcomes on the training dataset
o Evaluate and print:
▪ Precision
▪ Recall
▪ Confusion Matrix

• Additionally, create a different test dataset (new/different examples) to measure
model performance independently.
Deliverables: Python script, model performance metrics (precision, recall, confusion
matrix) on both training and test datasets.
Step 2: Model Improvement
• Iteratively improve the model’s performance.
• You must achieve at least a 20% improvement in model evaluation metrics
(precision/recall/F1-score) compared to your initial model.
• Show clearly the before and after performance.
• Explain briefly the techniques used (e.g., hyperparameter tuning, feature
engineering, algorithm change, etc.).

Deliverables: Updated model script, performance comparison chart/table, and brief notes
on improvement techniques.
Step 3: Build an API
• Build a simple API (Flask or FastAPI) that:
o Accepts a text input
o Uses your final model to predict and return the result.
• Provide instructions to run the API locally.
Deliverables: API code, example API call and response format.

Marking Criteria
• 40% — Model building (dataset preparation, training, evaluation)
• 40% — Model improvement (performance boost and documentation)
• 20% — API development (working and clean endpoint)


for this problem i have a dataset that contain 500 rows of a dataframe and these rows are untructured bangla sentences with different topics. How do i proceed with the task
