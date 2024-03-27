<h1 align="center" id="title">Internet Crawler</h1>

<p id="description">A Flask app that’s like a digital spider 🕷️ crawling the web 🌐 based on user queries. Whether you’re hunting for information entertainment or anything else 🐱 my app’s got you covered! 🙌</p>

<p align="center"><img src="http://ForTheBadge.com/images/badges/made-with-python.svg" alt="shields"></p>

<h2>🚀 Demo</h2>

[https://internet-crawler-beta.onrender.com/](https://internet-crawler-beta.onrender.com/)

<h2>Project Screenshots:</h2>

<img src="https://bg-so-1.zippyimage.com/2024/03/27/63a983e04a466582fbbfb9606ce5c57a.png" alt="project-screenshot" width="100%" height="400/">

  
  
<h2>🧐 Features</h2>

Here're some of the project's best features:

*   🖇 Links Crawler: It scours the internet for relevant links based on user input.
*   ⚠ IP Display: It also reveals the user’s IP address (with their consent of course!).
*   ⏳ Loading Page: While results are being fetched users get a slick loading page .
*   📢 Automatic Alerts: As soon as the results are ready users receive an alert.
*   ✨ Asynchronous Magic: I’ve sprinkled in some asynchronous magic for efficiency.
*   🖥 Tailwind CSS: The frontend is sleek and responsive thanks to Tailwind CSS.
*   🦄 Gunicorn: Flask’s built-in server isn’t production-ready so I’ve enlisted Gunicorn
*   🧵 Multithreading: To handle multiple users concurrently I’ve added multithreading .
*   🗝 Unique IDs: Each user gets a unique ID to retrieve their results .
*   🔐 Flask SSLify: Security matters! I’ve secured it with Flask SSLify .

<h2>🛠️ Installation Steps:</h2>

<p>1. An extremely fast Python package installer and resolver written in Rust.</p>

```
pip install uv
```

<p>2. Create Virtual Environment</p>

```
uv venv
```

<p>3. Activate Virtual Environment</p>

```
source .venv/bin/activate    # For macOS, Linux
.venv\Scripts\activate       # For Windows
```

<p>4. To install all the packages in Virtual Environment</p>

```
uv pip install -r requirements.txt  
```

<p>5. To run app</p>

```
gunicorn app:app
```

  
  
<h2>💻 Built with</h2>

Technologies used in the project:

*   Tailwind CSS
*   Flask
