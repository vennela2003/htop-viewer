# htop-viewer

# 🖥️ HTOP Viewer - Flask Web App

This is a simple Flask-based web application that displays the output of the `htop` command (system monitoring) along with the system user's name and the current time in IST (Indian Standard Time).

---

## 📌 Features

- Displays live system resource usage using the `top` command.
- Shows your system username and current IST time.
- Built using **Python Flask**.
- Easy to deploy and run on GitHub Codespaces.

---

## 🛠️ Technologies Used

- Python 3
- Flask
- Subprocess module
- pytz for timezone handling

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/htop-viewer.git
cd htop-viewer


2. Install dependencies

pip install flask pytz

3. Run the application

python app.py


🌐 Live Demo (GitHub Codespaces)
If you're using GitHub Codespaces:

Click on the Ports tab at the bottom.

Make Port 5000 Public.

Access the app via the generated URL and go to /htop
Example: https://your-url.app.github.dev/htop
