"# DataScrape-Application" 

Overview
This Data Scraping Application is designed to extract data from web pages, focusing on links and images. The application is built using Django and allows users to specify target websites, automatically retrieving and storing relevant data for further analysis or use.

Features
Link Extraction: Automatically retrieve all hyperlinks from specified web pages.
Image Extraction: Download and store images from web pages.
Data Storage: Store extracted data, including links and images, in a structured format.
Image Handling: Efficiently handle and store images for easy access.
Technologies Used
Backend: Django, Python
Frontend: HTML, CSS, JavaScript
Database: SQLite (can be configured to use PostgreSQL, MySQL, etc.)
Web Scraping: BeautifulSoup, Requests
Image Handling: Pillow (PIL)
Installation
Prerequisites
Python 3.7.9
Django
pip
Virtualenv (recommended)
Setup
Clone the repository:


git clone https://github.com/maariraj/data-scraping-app.git
cd data-scraping-app
Create a virtual environment:


python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
Install dependencies:


pip install -r requirements.txt
Apply migrations:

python manage.py migrate
Run the server:


python manage.py runserver
Access the application:

Open your web browser and navigate to http://localhost:8000.

Usage
Add a New Scraping Task:

Navigate to the "New Task" page.
Enter the URL and specify the data points (links, images) to scrape.
View Data:

View the extracted links and images in the application.
Download Images:

Download and store images locally from the specified URLs.

Contributing
Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes and commit them (git commit -m 'Add some feature').
Push to the branch (git push origin feature-branch).
Open a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
If you have any questions or need further assistance, feel free to reach out to the project maintainer:

Name: Mari Raj M.
GitHub: maariraj
Twitter: mari_raj57248
