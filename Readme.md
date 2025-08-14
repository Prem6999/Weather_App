# Welcome to the README for This Project 🚀

Let’s get straight to the point — to fully implement this project, follow the steps below.

---

## 1️⃣ Clone the Repository

```bash
git clone "https://github.com/Prem6999/Weather_App".git
```

---

## 2️⃣ Create a Virtual Environment

**For Windows:**
```bash
python -m venv env
```

**For Mac:**
```bash
python3 -m venv env
```

``` bash
cd env
```

---

## 3️⃣ Activate the Virtual Environment

**For Windows:**
```bash
env\Scripts\activate
```

**For Mac:**
```bash
source env/bin/activate
```

✅ You now have your virtual environment set up successfully.

---

## 4️⃣ Install Required Modules

All required dependencies are listed in `requirements.txt`. Install them with:

```bash
pip install -r requirements.txt
```

💡 These dependencies are automatically handled with the included `.pylintrc` and `.vscode/settings.json` files.  
No manual setup is needed — just open the project in **VS Code** and make sure your Python virtual environment is activated.

---

## 5️⃣ Configure Your API Key

In the `main.py` file, find the variable named:

```python
api_key = ""
```

Replace the empty string with your own API key.

You can get your API key by:
1. Signing up at **[https://openweathermap.org]**
2. Clicking your profile icon
3. Selecting **"My API Keys"** from the dropdown
4. Copying your API key and pasting it into `api_key`.

---

✅ That’s it! You’re all set to run the project. Enjoy coding! 🎉
