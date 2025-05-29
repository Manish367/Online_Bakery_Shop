# 🧁 Bakery Shop - Django Project

A simple Django-based web application for managing an online bakery and grocery shop. It includes features for browsing products, managing inventory, user authentication, and order processing.

---

## 🚀 Features

- 🛒 Product listing and categorization (e.g., Bakery, Grocery)
- 👥 Admin dashboard (add/edit/delete products)
- 🔐 User registration and login
- 📦 Cart and basic order management
- 💾 SQLite3 database integration
- 📁 Media support for product images

---

## 🛠 Tech Stack

- **Backend:** Python, Django
- **Database:** SQLite3
- **Frontend:** HTML, CSS (via Django templates)
- **Others:** Django Admin, Virtual Environment

---

## 📂 Project Structure

BakeryShop/
├── db.sqlite3 # SQLite database file
├── manage.py # Django project manager
├── grocery/ # App for product management
├── media/ # Uploaded media (e.g. product images)
├── Online_Grocery_Shop/ # Project settings and URLs


---

## ⚙️ Setup Instructions

### 1. Clone the repository

git clone https://github.com/your-username/bakery-shop.git
cd bakery-shop

2. Create and activate a virtual environment

python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On macOS/Linux

3. Install dependencies

pip install django pillow

4. Run migrations

python manage.py migrate

5. Create superuser (for admin access)

python manage.py createsuperuser

6. Start the server

python manage.py runserver

Go to http://127.0.0.1:8000 to view the app.

🔐 Admin Panel
Visit http://127.0.0.1:8000/admin
Login using the credentials you created in the createsuperuser step.

📸 Screenshots (Optional)
Add screenshots of your app here if available.

🙌 Acknowledgements
Built with Django

Icons or template credits if used

📃 License
This project is licensed under the MIT License.
