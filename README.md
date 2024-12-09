# Predicting-Out-of-Stock

📚 Overview

This project tackles the challenge of Out-of-Stock (OOS) events in retail, a significant issue for manufacturers and retailers alike. We designed and implemented machine learning-based systems to predict OOS events effectively, focusing on a Latin American packaged foods manufacturing company.

🚀 Key Features

	•	Machine Learning Models: Developed a Random Forest classifier and an ensemble of six algorithms to detect OOS events.
	•	Innovative Predictors: Introduced novel variables from sales, inventory, and ordering data to improve prediction accuracy.
	•	Real-World Validation: Achieved 72% precision and 68% recall in detecting OOS events in a live retail setting.

 🛠 Methodology

	1.	Data Collection: Leveraged transactional data (e.g., sales, inventory, orders) and physical audits.
	2.	Feature Engineering: Designed 68 predictor variables across seven categories: sales, inventory, product, context, ordering, supply chain, and description.
	3.	Model Training: Evaluated Random Forest, Neural Networks, and an ensemble model using R with extensive hyperparameter tuning.
	4.	Performance Metrics: Focused on F-measure, precision, and recall to ensure actionable and reliable predictions.

 🔍 Results

	•	The ensemble model outperformed others, combining strengths of diverse algorithms.
	•	Inclusion of new predictor variables improved Random Forest’s F-measure by 0.24 points.
	•	Successfully implemented in a real-world retail environment with impactful results.
