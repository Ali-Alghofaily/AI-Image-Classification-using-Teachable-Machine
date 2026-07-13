# AI-Image-Classification-using-Teachable-Machine

# AI Vehicle Classification (Sedan vs. Truck)

An interactive Image Classification project developed as part of my training program. This project utilizes **Google's Teachable Machine** to train a machine learning model to classify vehicles into two primary categories: **Sedan** and **Truck**, and deploys/tests the model using **Google Colab**.

---

## 🚀 Project Workflow

1.  **Data Collection & Labelling:** Gathered and uploaded sample images for two classes:
    *   **Sedan:** 4 samples of passenger sedan cars.
    *   **Truck (truk):** 4 samples of various commercial and transport trucks.
2.  **Model Training:** Trained a deep learning model directly in the browser using Teachable Machine's transfer learning framework.
3.  **Testing & Validation:** Tested the trained model with new vehicle images. (e.g., A red sedan achieved a **59% confidence score** for the `sedan` class during live testing).
4.  **Colab Integration:** Exported the trained model (TensorFlow/Keras format) and executed predictions using a **Google Colab** notebook.

---

## 🛠️ Tech Stack & Tools

*   **Google Teachable Machine:** For quick data gathering, labeling, model training, and instant validation.
*   **Google Colab:** Used to run python code for loading the exported model, processing input images, and running classification predictions.
*   **TensorFlow / Keras:** The underlying deep learning frameworks utilized for executing the exported model (`.h5` or `SavedModel` format).

---

## 📊 Evaluation & Future Improvements

### Current Limitations:
*   **Dataset Size:** The initial prototype was trained on a minimal dataset (4 images per class), which is sufficient for a proof of concept but limits general accuracy.
*   **Confidence Scores:** Some test images yield split predictions (e.g., 59% Sedan vs 41% Truck) due to the small variety of training samples.

### Proposed Upgrades:
*   **Expand Dataset:** Increase training dataset to 100+ images per class to capture different angles, lighting conditions, and vehicle colors.
*   **Hyperparameter Tuning:** Adjust the training epochs and learning rate in Google Colab to improve the model’s convergence and prediction accuracy.

---

## 💻 How to Run the Model on Colab

1. Export your model from Teachable Machine as a **TensorFlow (Keras)** model (`keras_model.h5` and `labels.txt`).
2. Upload the exported files to your Google Colab environment.
3. Use the following Python code snippet to run predictions on your test images:

<img width="938" height="503" alt="Screenshot 2026-07-13 233940" src="https://github.com/user-attachments/assets/62573da2-1fa4-43ae-a62f-4956b0ab9dc5" />
