## Title: FlavorSwift: DialogFlow Powered Food Ordering

### Overview:
FlavorSwift is a sophisticated food ordering system built on the synergy of Natural Language Processing (NLP), DialogFlow, FastAPI, and MySQL Database. This project allows users to seamlessly place and manage food orders using a DialogFlow-powered chatbot named FlavorSwift.


### A. Key Features
* **Conversational Ordering:** Users can place new orders, add or remove items, and track their orders through an intuitive chatbot interface.

* **DialogFlow Integration:** FlavorSwift leverages DialogFlow to understand user intents and parameters, providing a natural and interactive ordering experience.

* **FastAPI Backend:** The backend is powered by FastAPI, a modern, fast web framework for building APIs with Python 3.7+ based on standard Python type hints.

* **MySQL Database:** FlavorSwift utilizes a MySQL database for efficient storage and retrieval of order details and tracking information.

* **Ngrok Integration:** Ngrok is employed for secure and reliable tunneling, ensuring seamless communication between the FastAPI server and external services.

### B. Project Structure

* **main.py:** The main FastAPI application handling incoming requests, processing DialogFlow intents, and managing orders.

* **generic_helper.py:** Contains utility functions for extracting session IDs and formatting order details.

* **db_helper.py:** Manages interactions with the MySQL database, including order item insertion, order tracking, and status retrieval.

* **home.html** and **style.css:** Frontend files providing a user-friendly interface for placing and tracking orders.


### C. How to Run

* Ensure Python, FastAPI, DialogFlow, and MySQL are properly installed.
* Set up a MySQL database with the provided 3. credentials in **'db_helper.py'**.
* Run **pip install -r requirements.txt** to install all required packages.
* Run the FastAPI server using **'uvicorn main:app --reload'**.
* Expose the server using Ngrok.
* Configure DialogFlow to communicate with the Ngrok-exposed endpoint.
* Interact with FlavorSwift through the DialogFlow-powered chatbot.



### Acknowledgments:

* Special thanks to the open-source communities behind FastAPI, DialogFlow, and Ngrok for their invaluable contributions.


-- Explore the FlavorSwift experience and enjoy a seamless food ordering journey!


## 🔗 Link
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abhishek-sachin-deshmukh/)


## Authors

- [@abhishekdeshmukh001](https://github.com/abhishekdeshmukh001)
