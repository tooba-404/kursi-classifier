# kursi-classifier

## 📄 Description
This is a browser-based object classification tool developed for the **Critical Thinking Assignment (Spring 2025)** at Bahria University.

It allows users to upload an image of a plastic object (Black, Transparent, or Colorful), analyzes the average brightness using JavaScript, and assigns it to the correct conveyor belt:

- **Conveyor A** → Black objects (low brightness)
- **Conveyor B** → Transparent objects (high brightness)
- **Conveyor C** → Colorful objects (medium brightness)

No backend or server is required – runs fully in the browser.

---

## 🚀 Technologies Used

- HTML5
- CSS3 (custom styling)
- JavaScript (Canvas API)

---

## 📦 How to Run

1. Download or clone the repository.
2. Open the `index.html` file in any modern browser (Chrome, Firefox, Edge, etc.).
3. Upload an image and view the result instantly.

---

## 📁 Project Structure

```
kursi-classifier/
├── index.html        # Main application file (HTML/CSS/JS combined)
├── sample-images/    # Sample test images for demo
└── README.md         # This file
```

---

## 🧠 Classification Logic

The system calculates the **average brightness** of the uploaded image using this formula:

```text
Brightness = 0.299 * R + 0.587 * G + 0.114 * B
```

Based on the result:
- Brightness > 170 → Transparent → Conveyor B
- Brightness < 80 → Black → Conveyor A
- Else → Colorful → Conveyor C

---

## 📷 Screenshots

![image](https://github.com/user-attachments/assets/4286d29b-7636-4f9b-b82d-e3e9f541dd29)
![image](https://github.com/user-attachments/assets/bdd57a44-5221-4e1b-a5ee-db1663ca555b)
![image](https://github.com/user-attachments/assets/53bc9b7d-3e01-4244-9ef0-b44ddb55bfef)

---

## 🎓 Academic Info

**Course**: BES-103 Critical Thinking  
**Institution**: Bahria University  
**Semester**: Spring 2025

