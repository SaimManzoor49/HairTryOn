# AI Barbershop: Virtual Hairstyle Try-On

This project provides an interactive web application using **Gradio** to virtually apply different hairstyles to a user's photo. It leverages a powerful AI model to perform realistic hairstyle transfers.

> 💡 _Tip: Replace this note with an actual screenshot of your app for better visual presentation!_

---

## 🔑 Key Features

- **Interactive Hairstyle Gallery**  
  Browse and visualize all available hairstyles directly in the app.

- **Click-to-Select**  
  Simply click on a hairstyle from the gallery to select it—no need to manually type filenames.

- **One-Click Hairstyle Transfer**  
  Upload your photo, select a style, and let the AI do the rest.

- **Real-time Logging**  
  Monitor the entire process, from face alignment to final image generation, with logs displayed live in the console.

- **Dual API Endpoints**  
  - `apply_hairstyle`: Programmatically apply a hairstyle to an image.  
  - `get_hairstyles`: Fetch a JSON list of all available hairstyle filenames.

---

## ⚙️ How It Works

1. **Face Alignment**  
   The uploaded photo is processed to align the face properly.

2. **AI Inference**  
   A pre-trained model blends the selected hairstyle onto the aligned face.

3. **Result Generation**  
   The final, high-quality image with the new hairstyle is displayed.

---

## 🚀 How to Use

1. **Run the Application**  
   Launch the `app.py` script.

2. **Open the Web Interface**  
   Access the provided Gradio link in your browser.

3. **Navigate to the "Apply Hairstyle" Tab**
   - Upload a clear, front-facing photo.
   - Browse the gallery of available hairstyles.
   - Click any hairstyle image to select it.
   - Click the **Apply Hairstyle** button.

4. **View the Result**  
   The final image will appear in the "Result" panel.

---

