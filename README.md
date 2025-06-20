# 🍎🥦 Fruits & Vegetable Classification & Calories Counter Web App

## 📌 Introduction

This is a simple and interactive web application that classifies fruits and vegetables from images uploaded by the user. It not only predicts the name of the fruit or vegetable but also provides calorie information using web scraping.

## 🎥 Demo Video

▶️ [Watch Demo Video](https://drive.google.com/file/d/1yPMLwiikY3m8PHza4dgmISDG9PhcK76e/view?usp=sharing)

## 🚀 Features

- Upload an image of a fruit or vegetable.
- Automatically predicts the name using a deep learning model.
- Fetches and displays the calorie information of the predicted item.
- User-friendly interface accessible via any web browser.

## 🛠️ Tools & Libraries Used

| Tool / Library         | Purpose                                                |
|------------------------|--------------------------------------------------------|
| **Keras**              | Used for building and training the deep learning model |
| **Pillow**             | For image preprocessing                                |
| **Streamlit**          | Web app development framework                          |
| **BeautifulSoup** + `requests` | Web scraping for calorie data                         |
| **NumPy**              | Image matrix operations                                |

## 🧠 Model Architecture

The application uses **MobileNetV2**, a lightweight deep learning architecture optimized for mobile devices.

### MobileNetV2 Highlights:
- Uses inverted residual structures
- Efficient depthwise separable convolutions
- Suitable for 32x32+ image sizes

## 📂 Dataset

- **Source**: [Fruit and Vegetable Image Recognition Dataset on Kaggle](https://www.kaggle.com/kritikseth/fruit-and-vegetable-image-recognition)
- **Classes**: 36 categories of fruits and vegetables
- **Images**: ~3600+ training images (100 per class)

## 🔁 Workflow

1. User uploads an image via the Streamlit web app.
2. Image is preprocessed using Pillow (resized and converted to a model-compatible format).
3. Image is passed to the trained model for prediction.
4. The predicted class is mapped to its label.
5. Calories for the predicted item are fetched using web scraping.
6. Both the predicted name and calorie count are shown on the web interface.

## 🖼️ Output

The app displays:
- Uploaded image
- Predicted fruit/vegetable name
- Calories (scraped from the web)

## ✅ Conclusion

This project demonstrates how deep learning can be integrated into real-world applications that are accessible to everyday users through a browser. It showcases the use of image classification and dynamic data fetching using Python libraries.




