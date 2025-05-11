# DevSpace (Django Portfolio Website)

This project is a personal portfolio website built with Django.  
It showcases my skills in Python, Machine Learning (ML), Artificial Intelligence (AI), web scraping, automation, and web development.

## 🚀 Features

- Professional portfolio homepage
- About section describing skills and experience
- Services dropdown (Web Development, App Development, SEO Services)
- Contact information with email and clickable phone number
- Mobile responsive design (Tailwind CSS + Alpine.js)
- Blog section (future updates planned)

## 🛠️ Tech Stack

- **Frontend**: Tailwind CSS, Alpine.js
- **Backend**: Django
- **Database**: PostgreSQL (default, can be upgraded to MongoDB/MySQL)
- **Deployment Ready**: Can be hosted on platforms like Vercel, Render, or AWS.

## 📁 Project Setup

Follow these steps to run the project locally:
	
```bash
# 1. Clone the repository
git clone https://github.com/pravin-python/DevSpace/

# 2. Navigate to the project directory
cd DevSpace

# 3. Create a virtual environment
python -m venv env

# 4. Activate the virtual environment
# For Windows
env\Scripts\activate

# For Mac/Linux
source env/bin/activate

# 5. Install required packages
pip install -r requirements.txt

# 6. Run migrations
python manage.py migrate

# 7. Start the Django development server
python manage.py runserver
