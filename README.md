# Face-Recognition-System
# 🧠 Advanced Face Recognition System (Google Colab)

This project is a **complete face recognition system** built using **DeepFace, OpenCV, and Python** inside **Google Colab**.
It includes:

✔ Uploading & storing known faces (database)
✔ Uploading test images for recognition
✔ 1:N face matching using **FaceNet**
✔ Gender & Emotion analysis (Age removed as requested)
✔ Auto attendance marking
✔ Face detection & bounding boxes
✔ Side-by-side match visualization
✔ Error-free & fully optimized for Colab

---

## 🚀 Features

### 🔹 1. Face Database

You can upload multiple known faces. All uploaded images are automatically saved into the `database/` folder.

### 🔹 2. Face Recognition (1:N Search)

Uses `DeepFace.find()` with the **FaceNet** model to match the input face against your database.

### 🔹 3. Advanced Analysis (without age)

* Gender detection (high accuracy)
* Emotion detection

### 🔹 4. Attendance System

The program automatically creates `attendance.csv` and marks:

* Person Name
* Date & Time

Duplicates are automatically prevented.

### 🔹 5. Face Detection (Bounding Boxes)

All detected faces are highlighted on the uploaded image using OpenCV.

### 🔹 6. Result Visualization

Displays:

* Test image
* Best match from the database
* Confidence score (%)

---

## 📦 Requirements

The following libraries are automatically installed in Colab:

```
deepface
opencv-python
matplotlib
pandas
numpy
Pillow
```

No manual installation needed outside Colab.

---

## ▶️ How to Run (Google Colab)

1. Open Google Colab
2. Create a new notebook
3. Copy–paste the **full code** from this repository into one cell
4. Run the cell
5. Upload:

   * Known images (database)
   * Test image(s)
6. View:

   * Best match
   * Gender & emotion
   * Bounding boxes
   * Attendance marked

---

## 📁 Project Structure

```
├── database/              # Uploaded known person images
├── attendance.csv         # Auto-generated attendance tracker
├── README.md              # Documentation
└── face_recognition.ipynb # Main Colab code
```

---

## 📊 Output Example

The program will detect:

* Best match from the database
* Confidence score (FaceNet)
* Gender & Emotion
* Bounding boxes around detected faces

Example:

```
🎯 BEST MATCH: Chris_Hemsworth (97.2%)
Gender: Man (99.99%)
Emotion: neutral
✔ Attendance Marked for Chris_Hemsworth at 2025-11-29 12:45:52
```

---

## 🛠 Technologies Used

| Technology | Purpose                           |
| ---------- | --------------------------------- |
| DeepFace   | Face recognition & analysis       |
| FaceNet    | Feature extraction model          |
| OpenCV     | Image processing & face detection |
| Pandas     | Attendance storage                |
| Matplotlib | Visualization                     |
| Colab      | Execution environment             |

---

## 📌 Notes

* Age estimation has been intentionally **removed**.
* Gender prediction is made more accurate using probability scoring.
* Facial area extraction is corrected to avoid “too many values to unpack”.

---

## 🧩 Future Enhancements (Optional)

You can extend this project with:

* Live camera detection
* Face recognition in videos
* Voice alert when match found
* Database organized by folder names (classification)
* Multi-face recognition at once

Tell me if you want any of these features added — I can generate complete code for them.

---

## 📝 License

This project is open-source and free to use.

<img width="619" height="669" alt="image" src="https://github.com/user-attachments/assets/b02f4fc4-2b81-40a0-955c-646ce582ba62" />
<img width="899" height="683" alt="image" src="https://github.com/user-attachments/assets/479e0857-c27a-402b-8a7a-9febc8a0f242" />
<img width="586" height="705" alt="image" src="https://github.com/user-attachments/assets/5d682bd8-fa19-45e9-924f-b665344b3781" />

