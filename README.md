
# MobileNetV2-FoodClassifier

This project utilizes a dataset acquired via web scraping from Unsplash, comprising diverse high-quality food ingredient images.

Employing transfer learning with MobileNet V2 for feature extraction, fine-tuning, and hyperparameter tuning, various models are trained for image classification.

The selected model is converted into TensorFlow Lite format for efficient deployment on mobile and edge devices, ensuring practical application in real-world scenarios.


## Model Predictions

![App Screenshot](https://drive.google.com/file/d/1hiqzyrS75f4KJIsTzILpYZuiMikAh-Xy/view?usp=sharing)

## Table of Contents

- [Run Locally](#run-locally)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Model Predictions](#model-predictions)
- [Evaluation](#evaluation)
- [Dependencies](#dependencies)
- [License](#license)
- [Author](#author)
- [Contributors](#contributors)

## Run Locally

1. Clone this repository using the following command
```bash
  git clone https://github.com/Pramit726/MobileNetV2-FoodClassifier.git
```

2. Create a new python virtual environment

```bash
  python -m venv your-envirorment-name
```
3. Activate your created python virtual environment

```bash
  your-envirorment-name\Scripts\activate
```

4. Install the required dependencies

```bash
  pip install -r requirements.txt
```
5. Now you are all set.

    
## Dataset

The dataset is collected via web scrapping through Unsplash.

If you want to use the exact dataset as ours you can download from here:

https://drive.google.com/file/d/1JsY1u6MIEwGQN6ilFBm3a1w18HmA9nfj/view?usp=drive_link

## Model Architecture

- **Base model:** MobileNet V2, known for its efficiency and accuracy.
- **Feature extraction:** Utilized MobileNet V2's pre-trained weights to capture key features from food ingredient images.
- **Fine-tuning:** Modified MobileNet V2's architecture, focusing on fine-tuning parameters from block 6 onwards to optimize performance for the food ingredient dataset.
- **Model architecture diagram:** 

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
## Evaluation

- Evaluation conducted on test data.
- Achieved accuracy: 93.14%.
- **Classification report:** 

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
- **Confusion matrix:** 

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

## License
Distributed under the MIT License. See **LICENSE** for more information.

## Dependencies

- BeautifulSoup
- Keras Tuner
- Matplotlib
- NumPy
- Pillow
- Requests
- Scikit-Learn
- Seaborn
- TensorFlow

## Author

**[Deepmalya Rakshit](https://github.com/Deepmalya-Rakshit)**
- deepmalyarakshit@gmail.com
-  Department of CSE, Techno International New Town, West Bengal, India


## Contributors

 **[Pramit De](https://github.com/Pramit726)**  
 - pramitde726@gmail.com / pramit.de.cse.2021@tint.edu.in 

- Department of CSE, Techno International New Town, West Bengal, India 

**© 2024 MobileNetV2-FoodClassifier by Deepmalya Rakshit** 