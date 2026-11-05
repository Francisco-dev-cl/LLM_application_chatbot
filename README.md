# LLM Application Chatbot

This repository contains an application designed to transition a foundational large language model conversational workflow into a fully functional web-based deployment.

## 🎯 Project Objective

The goal of this project is to take a command-line Large Language Model (LLM) chatbot and embed it into a production-ready web layout, allowing users to interact with generative text models via a graphical browser user interface.

## 📁 Repository Structure

* **`app.py`**: The main Flask/backend server entry point configuring app routes, processing web requests, and communicating with the LLM layer.
* **`templates/`**: HTML view documents structuring the structure and elements of the front-end interface.
* **`static/`**: Contains client-side operational files like style sheets (CSS) and interactivity scripts (JavaScript).
* **`Dockerfile`**: Containerization recipe for building an independent image to deploy the application seamlessly across cloud platforms.
* **`requirements.txt`**: Consolidated index pinning the specific library versions required to stand up the environment.

## 🛠 Technologies Used

* **Core Platform:** Python 3.x, Flask
* **Deployment/MLOps:** Docker
* **Frontend Design:** HTML5, CSS3

## 🚀 Installation and Execution

### Local Environment Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd LLM_application_chatbot
   ```

2. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the server:**
   ```bash
   python app.py
   ```

### Docker Container Deployment

If you prefer isolating execution context within a container ecosystem:

1. **Build the container image:**
   ```bash
   docker build -t llm-web-app .
   ```

2. **Run the container instance:**
   ```bash
   docker run -p 5000:5000 llm-web-app
   ```

## 📈 Demonstrated Skills

* **Full-Stack AI Engineering:** Seamless integration linking standard Python NLP backends directly into interactive user web platforms.
* **Containerization & Devops:** Engineering reliable `Dockerfiles` ensuring configuration immutability from development environments straight to cloud platforms.
* **State Management:** Structuring server routing capable of tracking multi-turn web payloads efficiently.
