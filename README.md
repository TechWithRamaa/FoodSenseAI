# FoodSenseAI

- The project is built upon the **principles of deep learning** and incorporates advanced techniques to **classify a dataset containing 16,643 food images grouped into 11 categories**

- **Dataset** from [kaggle](https://www.kaggle.com/datasets/vermaavi/food11/data)
- Built while learning from [coursera](https://www.coursera.org/projects/transfer-learning-food-classification)

- **Skills** -> Computer Vision | Image Classification | Python | Tensorflow | Keras | CNN | Transfer Learning | PreTrained Models
- **Implementation** -> [food_sense_ai.ipynb](https://github.com/TechWithRamaa/FoodSenseAI/blob/main/food_sense_ai.ipynb)

**Data Handling and Preparation:**
* Utilizes Pandas and NumPy for efficient data manipulation
* Real-time data augmentation is achieved using ImageDataGenerator to improve model generalization

# Model Architecture
* Employs **Convolutional Neural Networks (CNNs) for feature extraction** from food images
* Integrates **pre-trained model InceptionResNetV2** through **transfer learning** to leverage learned features, enhancing classification accuracy

**Optimization and Training:**
* Uses **Stochastic Gradient Descent (SGD)** and other advanced optimizers for effective learning
* Implements **callbacks** to manage learning rates, prevent overfitting, and save the best model versions

**Visualization and Analysis:**
* Employs **Matplotlib and Seaborn** for visualizing data distributions, model performance, and training metrics
