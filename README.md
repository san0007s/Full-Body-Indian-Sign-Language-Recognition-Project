


# **Full-Body Indian Sign Language (ISL) Recognition System**

This project develops an **AI-based recognition system** for **Indian Sign Language (ISL)** using **full-body landmarks**, including **hand signs, body posture, and facial expressions**. Unlike traditional models that rely only on hand gestures, this approach enhances **context and accuracy** by combining multiple visual cues.

---

## **Key Features**

✔ **Full-Body Landmark Detection** using **MediaPipe Holistic** & OpenCV
✔ **Temporal Gesture Recognition** with **LSTM**
✔ **Start/End Detection** using **GHMM**
✔ **Baseline Model**: Random Forest for performance comparison
✔ Supports **real-time recognition** and **video input**

---

## **Tech Stack**

* **Language:** Python
* **Libraries:** OpenCV, MediaPipe, NumPy, Pandas, TensorFlow/Keras, scikit-learn
* **Models:** LSTM, GHMM, Random Forest

---

## **Project Workflow**

1. **Landmark Extraction**

   * Extracts pose, hand, and face coordinates using MediaPipe
2. **Data Preprocessing**

   * Normalization and feature engineering
3. **Modeling**

   * **LSTM:** Captures sequential gesture patterns
   * **GHMM:** Identifies start and end of gestures
   * **Random Forest:** Baseline classification
4. **Evaluation**

   * Accuracy, F1-score, confusion matrix
5. **Visualization**

   * Training curves, gesture examples, prediction outputs

---

## **Installation**

```bash
git clone https://github.com/san0007s/Full-Body-Indian-Sign-Language-Recognition-Project.git
cd Full-Body-Indian-Sign-Language-Recognition-Project
pip install -r requirements.txt
```





## **Output**

* Displays recognized ISL signs as **text on screen**
* Converts text to **speech output** (optional)

---

## **Future Scope**

* Expand ISL vocabulary
* Deploy as a **mobile/web app**
* Add **speech-to-sign translation**

---

## **Project Goal**

To **bridge the communication gap** for the deaf and hard-of-hearing community using AI-powered sign language recognition.

---

