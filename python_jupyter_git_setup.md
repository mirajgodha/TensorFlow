# Python, Jupyter Lab, and Git Setup Guide for Windows

## 1. Install Python on Windows

**Step 1.1 – Download Python:**

1. Open your browser and go to: [https://www.python.org/downloads/windows/](https://www.python.org/downloads/windows/)
2. Click the latest version download link for Windows.
3. Once downloaded, open the installer.

**Step 1.2 – Install Python:**

1. On the first screen, check the box: `Add Python to PATH`
2. Click **Install Now** and wait until the installation completes.

**Step 1.3 – Verify Installation:**

1. Press **Windows + R**, type `cmd`, press **Enter**.
2. In the Command Prompt window, type:

```
python --version
```

You should see something like: `Python 3.x.x`

---

## 2. Install Jupyter Lab

**Step 2.1 – Create a Virtual Environment:**

```
python -m venv myenv
myenv\Scripts\activate
```

**Step 2.2 – Install Jupyter Lab:**

```
pip install jupyterlab
```

**Step 2.3 – Verify Installation:**

```
jupyter lab --version
```

---

## 3. Install Git

**Step 3.1 – Download Git:** Go to [https://git-scm.com/download/win](https://git-scm.com/download/win)

**Step 3.2 – Install Git:** Run the installer and keep default settings.

**Verify Installation:**

```
git --version
```

---

## 4. Download Code from GitHub

**Step 4.1 – Open Command Prompt:** Press **Windows + R**, type `cmd`, press **Enter**.

**Step 4.2 – Navigate to the desired folder:**

```
cd C:\Users\YourName\Documents
```

**Step 4.3 – Clone the repository:**

```
git clone https://github.com/mirajgodha/TensorFlow.git
```

---

## 5. Install Requirements from the Repository

**Step 5.1 – Go to the Project Folder:**

```
cd TensorFlow
```

**Step 5.2 – Create and activate virtual environment:**

```
python -m venv venv
venv\Scripts\activate
```

**Step 5.3 – Install dependencies:**

```
pip install -r requirements.txt
```

---

## 6. Start Jupyter Lab

Run:

```
jupyter lab
```

This opens a new tab in your default browser with Jupyter Lab.

---

## Summary of All Commands

```
python --version
python -m venv myenv
myenv\Scripts\activate
pip install jupyterlab
git --version
git clone https://github.com/mirajgodha/TensorFlow.git
cd TensorFlow
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
jupyter lab
```

