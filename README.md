AI-Driven Citizen Grievance System

• Week 1: Data Collection, Text Cleaning, and EDA  
• Goal: Establish the repository and clean the raw citizen grievance text.  
• Tasks: Convert text to lowercase, remove special characters/URLs, and apply lemmatization.  
• Outputs: Generate Word Clouds and n-gram frequency distributions to visualize common complaints.  


• Week 2: Topic Modeling and Department Categorization  
• Goal: Route complaints to the correct government departments.  
• Tasks: Convert text into numerical vectors using TF-IDF or Word2Vec.  
• Modeling: Train a supervised classification model (like Logistic Regression or Random Forest) to map text to labels like "Sanitation" or "Transport".  


• Week 3: Sentiment Analysis and Urgency Scoring  
• Goal: Analyze the emotional tone and severity of the feedback.  
• Modeling: Train or fine-tune a model (like BERT or RoBERTa) to classify sentiment as Positive, Neutral, Negative, or Critical/Urgent.  
• Scoring: Assign a mathematical priority score to each ticket based on the detected sentiment.  


• Week 4: API Development, Evaluation, and Final Delivery  
• Goal: Deployment and performance assessment.  
• Evaluation: Use Confusion Matrices and Classification Reports to measure accuracy.  
• Deployment: Wrap the models in a FastAPI application that accepts JSON payloads and returns predicted departments and priority scores.
