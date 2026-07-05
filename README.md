# Wildlife Habitat Change Detection 🌍

A computer vision-based web application built with Flask and OpenCV that detects and analyzes changes in wildlife habitats by comparing satellite imagery taken at different time periods. This tool helps monitor environmental changes and aids in conservation efforts.

## ✨ Features
- **Satellite Analysis:** Upload and compare "before" and "after" satellite images of the same location.
- **Automated Change Detection:** Identifies structural and vegetation changes using computer vision (OpenCV).
- **Detailed Metrics:** Calculates precise change percentages (changed pixels vs. total area) to understand the severity of environmental impact.
- **Beautiful UI:** A responsive, aesthetic, and modern user interface styled with Tailwind CSS.

---

## 🛠️ Local Setup Guide

Follow these steps to run the project locally on your machine:

### Prerequisites
- Python 3.10 or higher installed on your system.
- Git installed.

### Installation Steps

1. **Clone the repository:**
   ```bash
   # Replace the URL with your actual repository URL if it differs
   git clone https://github.com/yourusername/leaf-nutrient-deficiency-by-Mavia.git
   cd leaf-nutrient-deficiency-by-Mavia
   ```

2. **Create a Virtual Environment (Recommended):**
   ```bash
   python -m venv venv
   
   # Activate on Windows
   venv\Scripts\activate
   
   # Activate on macOS/Linux
   source venv/bin/activate
   ```

3. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Application:**
   ```bash
   python app.py
   ```

5. **Access the App:**
   Open your web browser and navigate to `http://localhost:5000` or `http://127.0.0.1:5000`.

---

## 🚀 Hosting Guide

This project is perfectly configured to be hosted for free on **Render**.

### Deployment Steps (Render)
1. Make sure all your code is pushed to your GitHub repository. (The repository must include `requirements.txt` and `.python-version` set to a supported version like `3.10.13`).
2. Log in to [Render.com](https://render.com/) and go to your dashboard.
3. Click the **New +** button and select **Web Service**.
4. Choose **Build and deploy from a Git repository**.
5. Connect your GitHub account and select your repository.
6. Configure the deployment settings:
   - **Environment / Runtime:** `Python 3`
   - **Build Command:** `pip install -r requirements.txt`
   - **Start Command:** `gunicorn app:app`
7. Scroll down, select the **Free** instance type, and click **Create Web Service**.
8. Render will build and deploy your app. Once finished, you will receive a live `https://your-app-name.onrender.com` URL to access your project online!

*Note: Render's free tier uses ephemeral storage, which means uploaded images and generated result images are cleared when the server sleeps. This is standard and completely fine for this app since results are meant to be viewed instantly on the fly.*

---

## 👨‍💻 Developer

Developed by <a href="https://maviashariff.github.io/MavsPortfolio/#home" target="_blank" rel="noopener noreferrer">Mavia shariff</a>
