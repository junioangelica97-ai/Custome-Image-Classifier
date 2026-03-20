# Custom-Image-Classifier 
Google collab: https://colab.research.google.com/drive/1clij6b30ZchtJolTPHgXcHlHrR1BvIfL?usp=sharing


Guide Questions (Student Explanation & Reflection)
Students must answer:
Visualization & Overfitting

1. What signs indicated overfitting in your first model? 
Answer: Overfitting in the first model is evident because the model performed almost perfectly on the training data, but showed inconsistent performance on the validation data.

2. How did data augmentation affect validation accuracy?
Model Improvement
Answer: Data augmentation slightly lowered perfect accuracy but made the validation performance more stable and realistic, improving the model’s ability to generalize.

3. What is the purpose of dropout layers?
Answer: The purpose of dropout layers is to reduce overfitting and improve generalization of the model. Dropout helps prevent overfitting by randomly disabling neurons during training, making the model more generalizable and reliable.

4. Why does data augmentation improve generalization?
Performance Comparison
Answer: Data augmentation helps the model learn patterns, not just memorize images, which improves its ability to perform well on new data.

5. Compare accuracy before and after improvements.
Answer: Before the improvements, the model achieved very high accuracy (up to ~99–100%), but it was unstable, with sudden drops in validation accuracy (e.g., down to ~91%). This indicates overfitting—good performance on training data but inconsistent results on unseen data.
Before: Higher but unstable accuracy (overfitting)
After: Slightly lower but more stable and reliable accuracy (better generalization)

6. Which technique contributed most to improvement?
Answer: The technique that contributed most to improvement is data augmentation.
It had a bigger impact because it increased the variety of training data, helping the model learn more general patterns. While dropout helped reduce overfitting, data augmentation directly improved how the model performs on unseen data. 

Deployment & Application
7. Why is saving the model important?
Answer: Saving the model is important because it allows you to reuse the trained model without retraining it again. Training takes time and resources, so saving it lets you easily load the model later for prediction, testing, or deployment.

8. How can this model be deployed in a real-world system?
Answer: This model can be deployed by integrating it into an application or system, such as:
- A web app where users upload images and get predictions
- A mobile app for real-time image classification
- A backend API (e.g., using Flask or FastAPI) that processes images and returns results
