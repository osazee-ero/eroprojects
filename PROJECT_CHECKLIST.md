# LLM Portfolio Project Checklist

Use this checklist for every new LLM portfolio project.

## 1. Create GitHub Repository

* Create a public GitHub repo
* Add README
* Add Python `.gitignore`
* Add MIT License

## 2. Add Basic Files

Required files:

```text
README.md
requirements.txt
.env.example
app.py
```

Required folders:

```text
src/
notebooks/
screenshots/
examples/
```

Inside `src/`:

```text
__init__.py
main project logic files
utils.py
```

## 3. Create Professional README

README should include:

* Project title
* Project overview
* Problem
* Solution
* Tech stack
* Project structure
* Application workflow
* How to run
* Environment variables
* Status
* What I learned
* Demo
* Screenshots

## 4. Build Locally

* Create virtual environment
* Install dependencies
* Run app locally
* Test main features

```bash
python -m venv venv
venv\Scripts\activate
python -m pip install -r requirements.txt
python -m streamlit run app.py
```

## 5. Protect API Keys

* Put real keys only in `.env`
* Put example keys only in `.env.example`
* Never commit `.env`
* Check `git status` before every commit

## 6. Add Core Features

* Build the main app logic
* Add error handling
* Add clean UI
* Add useful output
* Add download/export feature if useful

## 7. Add Screenshot

* Run the app
* Take screenshot
* Save inside:

```text
screenshots/app_screenshot.png
```

* Add screenshot to README:

```markdown
![App Screenshot](screenshots/app_screenshot.png)
```

## 8. Deploy App

Deploy with Streamlit Community Cloud.

Deployment settings:

```text
Repository: project repo
Branch: main
Main file path: app.py
Secrets: add API keys safely
```

## 9. Update Links

Add live demo link to:

* Project README
* Portfolio website project card

## 10. Mark Project Complete

On portfolio website:

* Change status from `Planned` or `In Progress` to `Completed`
* Update description
* Add GitHub link
* Add Live Demo link

## Repeat for Next Project

For each new project:

```text
Create repo
Add structure
Build app
Document
Screenshot
Deploy
Update portfolio
Mark complete
```
