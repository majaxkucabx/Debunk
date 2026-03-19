# About the Project
**Debunk** is a web-based platform designed to verify misinformation found in online articles.

Users can report suspicious source articles found on the web.
Editors analyze the reported content.

Editors create a **Debunk Post**, which includes:
- link to the source article,
- verdict (True / False),
- justification explaining the reasoning,
- tags (e.g. Politics, Health, Science) for easy filtering.
Existing posts are displayed on the **Main Page**. Users can **upvote** posts they find useful

Users can apply to become **Editors** by submitting their CV through the platform and specifying their fields of expertise.
Upon approval, they receive permission to publish posts.

# Project Setup
Follow these steps to set up the project locally on your machine.

## Backend Setup
1. Navigate to the project root and create a virtual environment:

```
# Unix/macOS
python3 -m venv env

# Windows
python -m venv env
```

2. Activate the virtual environment:
```
# Unix/macOS
source env/bin/activate

# Windows (Command Prompt)
.\env\Scripts\activate.bat 

# Windows (PowerShell)
.\env\Scripts\Activate.ps1
```

3. Install dependencies:
```
pip install -r requirements.txt
```

4. Run the server:
```
cd backend
python manage.py runserver
```

## Frontend Setup
1. Navigate to the frontend directory:
```
cd frontend
```

2. Install dependencies (if you haven't installed packages yet):
```
npm install
```

3. Start the development server:
```
npm run dev
```

4. Access the application:
Open the link displayed in your terminal.


