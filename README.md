# ClassificationModel

# 🖼️ Custom Image Classifier (Transfer Learning + Streamlit UI)

## 📌 Project Overview

This project builds a custom image classification model using **transfer learning** with a pre-trained model (such as  / ) in  and .
It classifies images from a **small custom dataset** into categories like **cats, dogs, and other classes**.

---

## ⚙️ Key Features

* Uses **pre-trained model** as base.
* **Data augmentation** to improve model generalization.
* **Fine-tuning** of top layers for better accuracy.
* **Training & validation** on custom dataset.
* **Evaluation** using accuracy and **confusion matrix** on the test set.
* **Interactive user interface built with Streamlit** to:

  * Upload an image
  * Get prediction result in real time

---

## 📁 Dataset Structure

```
dataset/
│-- train/
│   │-- cat/
│   │-- dog/
│   │-- classname/
│
│-- val/   (validation)
    │-- cat/
    │-- dog/
    │-- classname/
```

---

## 💻 How to Run

1. Train the model
2. Save the model (`.keras` file)
3. Run the Streamlit app:

   ```bash
   streamlit run app.py
   ```
4. Upload an image to get the predicted class

---

## 📊 Output

* Training logs (accuracy & loss per epoch)
* Confusion matrix on test set
* Web interface prediction results

---

If you want, I can also **write the `app.py` file code** for the Streamlit interface.
Would you like me to do that next?
