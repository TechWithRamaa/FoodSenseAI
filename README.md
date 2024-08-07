# FoodSenseAI
Harnessing deep learning, convolutional neural networks, and transfer learning to classify and analyze food across 11 diverse categories.

FoodSenseAI processes a dataset containing 16,643 food images grouped into 11 categories, such as Bread, Dairy Product, Dessert, Egg, Fried Food, Meat, Noodles/Pasta, Rice, Seafood, Soup, and Vegetable/Fruit.
The project is built upon the principles of deep learning and leverages advanced techniques and tools to achieve high accuracy and performance.

Skills - Python | Tensorflow | Keras | CNN | Transfer Learning | PreTrained Models

Built while learning from https://www.coursera.org/projects/transfer-learning-food-classification

Data Handling and Preparation:
* Utilizes Pandas and NumPy for efficient data manipulation.
* Real-time data augmentation is achieved using ImageDataGenerator to improve model generalization.

Model Architecture:
* Employs Convolutional Neural Networks (CNNs) for feature extraction from food images.
* Integrates pre-trained model InceptionResNetV2 through transfer learning to leverage learned features, enhancing classification accuracy.

Optimization and Training:
* Uses Stochastic Gradient Descent (SGD) and other advanced optimizers for effective learning.
* Implements callbacks to manage learning rates, prevent overfitting, and save the best model versions.

Visualization and Analysis:
* Employs Matplotlib and Seaborn for visualizing data distributions, model performance, and training metrics.
* plot_model from Keras provides visual representations of the model architecture for better understanding.
