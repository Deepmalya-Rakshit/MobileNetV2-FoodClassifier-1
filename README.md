# MobileNetV2-FoodClassifier

This project utilizes a dataset acquired via web scraping from Unsplash, comprising diverse high-quality food ingredient images.

Employing transfer learning with MobileNet V2 for feature extraction, fine-tuning, and hyperparameter tuning, various models are trained for image classification.

The selected model is converted into TensorFlow Lite format for efficient deployment on mobile and edge devices, ensuring practical application in real-world scenarios.


## Model Predictions
![preview](https://github.com/Pramit726/MobileNetV2-FoodClassifier/assets/149934842/3a2b773f-07d2-4033-93ee-03cc25cba8a5)

## Table of Contents

- [Run Locally](🏃-run-locally)
- [Dataset](#📦-dataset)
- [Model Architecture](#🏗-model-architecture)
- [Evaluation](#📊-evaluation)
- [Model Deployment with TensorFlow Lite](#📱-model-deployment-with-tensorflow-lite)
- [Dependencies](#🛠-dependencies)
- [License](#📄-license)
- [Author](#🧑‍💻-author)
- [Contributors](#🤝-contributors)



## 🏃 Run Locally

1. Clone this repository using the following command.
bash
  git clone https://github.com/Pramit726/MobileNetV2-FoodClassifier.git


2. Create a new python virtual environment.

bash
  python -m venv your-envirorment-name

3. Activate your created python virtual environment.

bash
  your-envirorment-name\Scripts\activate


4. Install the required dependencies.

bash
  pip install -r requirements.txt

5. Now you are all set.

    
## 📦 Dataset

The dataset is collected via web scrapping through Unsplash.

If you want to use the exact dataset as ours you can download from here:

https://drive.google.com/file/d/1JsY1u6MIEwGQN6ilFBm3a1w18HmA9nfj/view?usp=drive_link

## 🏗 Model Architecture

- *Base model:* MobileNet V2, known for its efficiency and accuracy.
- *Feature extraction:* Utilized MobileNet V2's pre-trained weights on imagenet to capture key features from food ingredient images.
- *Fine-tuning:* Modified MobileNet V2's architecture, focusing on fine-tuning parameters from block 6 onwards to optimize performance for the food ingredient dataset.
- *Model architecture diagram:*

![model](https://github.com/Pramit726/MobileNetV2-FoodClassifier/assets/149934842/bf79373b-9634-4d38-8ae6-427fb036955b)


## 📊 Evaluation

- Evaluation conducted on test data.
- Achieved accuracy: 93.14%.
- *Classification report:*
  
![Screenshot 2024-04-28 113619](https://github.com/Pramit726/MobileNetV2-FoodClassifier/assets/149934842/2d89db7c-42c2-450f-bea4-5c23ed6cca18)


- *Confusion matrix:*

![Confusion_matrix](https://github.com/Pramit726/MobileNetV2-FoodClassifier/assets/149934842/d26da6db-5947-404f-8c17-28f5a6958f79)

## 📱 Model Deployment with TensorFlow Lite

To deploy our MobileNetV2-FoodClassifier on mobile and edge devices, we converted the trained TensorFlow model to TensorFlow Lite format. The converted model, optimized for efficiency, weighs approximately 11.9 MB. TensorFlow Lite ensures efficient on-device inference with minimal latency, making our model practical for real-world applications. For detailed deployment instructions, consult the [TensorFlow Lite documentation](https://www.tensorflow.org/lite/guide).


## 📄 License
Distributed under the MIT License. See LICENSE for more information.

## 🛠 Dependencies

- BeautifulSoup
- Keras Tuner
- Matplotlib
- NumPy
- Pillow
- Requests
- Scikit-Learn
- Seaborn
- TensorFlow

## 🧑‍💻 Author

*[Deepmalya Rakshit](https://github.com/Deepmalya-Rakshit)*
- deepmalyarakshit@gmail.com
-  Department of CSE, Techno International New Town, West Bengal, India

## 🤝 Contributors

 *[Pramit De](https://github.com/Pramit726)*  
 - pramitde726@gmail.com / pramit.de.cse.2021@tint.edu.in 

- Department of CSE, Techno International New Town, West Bengal, India 

**© 2024 MobileNetV2-FoodClassifier by Deepmalya Rakshit**