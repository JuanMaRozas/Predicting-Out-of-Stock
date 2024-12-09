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
 
 🌟 Why It Matters

Out-of-Stock events cause significant revenue losses and customer dissatisfaction. Our machine learning approach offers a scalable, data-driven solution to this critical supply chain challenge.

🛒 Use Case

	•	Designed for manufacturers aiming to predict OOS in collaboration with retail partners.
	•	Applicable across industries beyond packaged foods, wherever OOS is a concern. 

 📊 Performance
 
| Metric      | Random Forest | Ensemble |
|-------------|---------------|----------|
| Precision   | 73.5%         | 70.8%    |
| Recall      | 46.2%         | 56.7%    |
| F-measure   | 59.9%         | 66.5%    |

💡 Future Directions

	•	Explore deeper integration with real-time POS systems.
	•	Apply advanced deep learning methods for further performance gains.
	•	Expand to other regions and product categories.

🔗 Citation

For more details, refer to our published article:
Predicting Out-of-Stock Using Machine Learning: An Application in a Retail Packaged Foods Manufacturing Company
📄 DOI Link: https://www.mdpi.com/2079-9292/10/22/2787
