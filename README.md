# Flask App on Google App Engine ☁️

## 📍 About
A hands-on lab where I deployed a **Flask** file-upload app to **Google App Engine** using Cloud Shell, and got a live public URL for it.

## 🚀 Steps
1. **Create the App Engine application** from the console: choose a region (`us-central`) and the default service account.
2. **Open Cloud Shell** and get the app code:
   ```bash
   git clone https://github.com/CJ-2/upload-app.git
   cd upload-app/storage
   ```
3. **Test it locally** with `python main.py`, then use Cloud Shell's *Web Preview* on port 5000.
4. **Deploy** the app (type `y` to confirm):
   ```bash
   gcloud app deploy
   ```
5. **Open the live app:**
   ```bash
   gcloud app browse
   ```
6. **Check the deployment** in App Engine → Versions (Python 3.9, Standard environment, serving 100% of traffic).

## 📂 Files
- `Google cloud platform project lab3.pdf`: the full lab report with screenshots

**Tools:** Google App Engine · Cloud Shell · Flask · Python
