
# 🎬 Cinematic Director Assistant (Django Backend)

A Django-based backend application built to assist cinematic directors in their daily workflows. This project leverages AI-powered tools to enhance various aspects of film production, such as actor and filming location selection, and visual optimization.

## 🚀 Features

1. **Storyboard Generator**  
   Generates a visual storyboard (scene sketches) based on textual scene descriptions provided by the director.

2. **Trailer Generator**  
   Automatically creates a video trailer using few parameters like video URL, duration, and number of scenes.

3. **Lip Synchronization**  
   Generates a new version of a scene by syncing the actor’s video with updated dialogue, reducing the need for reshoots due to minor speech errors.

4. **Camera Location Suggestions**  
   Analyzes a scene’s video and provides suggested camera points for improved filming quality and scene composition.

5. **Chroma Keying (Green Screen Background)**  
   Replaces the background of a given scene image using a scene description, ideal for visualizing sets before filming.

---

## ⚙️ Getting Started

Follow these steps to set up and run the project locally:

### 1. Clone the Repository
```bash
git clone https://github.com/tayma-abed-rabh/Cinematic-Director-Assistant.git
cd Cinematic-Director-Assistant
```

### 2. Create and Activate a Virtual Environment

**On Windows:**
```bash
python -m venv venv
venv\Scripts\activate
```

**On macOS/Linux:**
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install -r requirements.txt
```
### 4. Make Migrations
```bash
python manage.py makemigrations
```

### 5. Apply Migrations
```bash
python manage.py migrate
```

### 6. Run the Development Server
```bash
python manage.py runserver
```

---

## 🛠 Configuration

Before running the project, make sure to update the configuration:

- Open `backend/settings.py`
- Configure necessary environment variables (especially the `DATABASES` section)

---

## 📌 Notes

- Make sure Python 3.12+ is installed.
- This project is backend-only.

---
