```markdown
 🌿 Plant Diseases Prediction

This is a machine learning-based web application that predicts plant diseases from leaf images using Convolutional Neural Networks (CNN). It is trained on the PlantVillage dataset and can identify a variety of plant diseases as well as healthy leaves with high accuracy.

🧠 Project Overview

- **Problem Statement**: Farmers often struggle to identify plant diseases accurately and on time. This project aims to provide an automated and accurate plant disease diagnosis tool using image classification.
- **Solution**: A web application that allows users to upload images of leaves and receive instant disease predictions.

📂 Dataset

- **Name**: [PlantVillage Dataset](https://www.kaggle.com/datasets/emmarex/plantdisease)
- **Classes**: Over 30 categories including both healthy and diseased leaves of various crops.

🛠️ Tech Stack

- **Frontend**: Streamlit
- **Backend**: Python
- **Model**: Convolutional Neural Network (CNN) built using TensorFlow/Keras
- **Deployment**: Streamlit Cloud / Localhost

📷 How It Works

1. Upload an image of a plant leaf.
2. The trained CNN model processes the image.
3. The application outputs the predicted disease (or "healthy") along with confidence.

🔍 Project Structure

```

├── app.py                # Streamlit application
├── model/
│   └── plant\_disease\_model.h5  # Trained CNN model
├── utils.py              # Image processing and prediction utilities
├── requirements.txt      # Python dependencies
└── README.md             # Project overview

````

 🚀 How to Run Locally

```bash
git clone https://github.com/yourusername/plant-diseases-prediction.git
cd plant-diseases-prediction
pip install -r requirements.txt
streamlit run app.py
````

 ✅ Example Results

![Prediction Example](example_images/result_demo.png)

 📌 Future Work

* Add support for more crop types.
* Improve accuracy with transfer learning.
* Build a mobile app version.

🤝 Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

 📄 License

This project is open-source under the [MIT License](LICENSE).

```
