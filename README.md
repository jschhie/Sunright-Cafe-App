# Cafe Ordering System

> - Full-stack cafe ordering system <br>
> - **Live demo:** https://sunrightcafe.pythonanywhere.com

---

## Tech Stack 
| Component | Tech Used |
| :--- | :--- |
| **Backend** | Python, Flask |
| **Data** | SQLite, SQL, JSON |
| **Frontend Logic** | JavaScript, Jinja Templating |
| **UI/Styling** | Bootstrap |
| **Deployment** | PythonAnywhere |

---

## Overview
* Full-stack Flask cafe ordering system
* Customizable drink options, search filters, and business hours restrictions
* Admin dashboard for managing the cafe database (WIP)

---

## 🔖 Table of Contents
* [Website Demo](https://github.com/jschhie/toast-tab-cafe/blob/main/README.md#website-demo)
* [Running the Website Manually](https://github.com/jschhie/toast-tab-cafe/blob/main/README.md#running-the-site-manually)

---

## Website Demo

### Cafe Menu
> (work in progress)
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/searchbar-1.png">

### Customize Drink 
> Required: sweetness, ice level, and milk type
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/updated-modal-1.png">

> Optional: toppings
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/updated-modal-2.png">

### Cart 
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/updated-cart-2.png">

### Receipt
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/receipt-1.png">

### Admin Dashboard (WIP)
> (WIP) Admin access to CRUD dashboard to manage Drinks, Toppings, MilkTypes, Orders, and CustomDrinks
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/Admin%20Home%20Page.png">
<img src="https://github.com/jschhie/toast-tab-cafe/blob/main/demos/admin-view-3-edit.png">

---

## Running the Site Manually
### 1. Clone this repository:
```bash 
git clone https://github.com/jschhie/toast-tab-cafe.git [folderNameHere]
```

### 2. Navigate into the folder: 
```bash 
cd [folderNameHere]
```

### 3. Create and activate virtual environment (`venv`):
> To isolate the project's dependencies

```bash
python3 -m venv venv
source venv/bin/activate
```

### 4. Install the required packages:
```bash
pip3 install -r requirements.txt
```

### 5. Configure environment variables
#### 5a. Create a `.env` file in the root directory:
```bash
vim .env
```

#### 5b. Open the `.env` file and define the following:
```
FLASK_SECRET_KEY=random_secret_key_here
FLASK_ADMIN_USERNAME=secret_admin_username_here
FLASK_ADMIN_PASSWORD=secret_admin_password_here
```

### 6. Run the Flask app:
```bash
python3 main.py
```

<p>The application will automatically generate a <code>cafe_database.db</code> file in the <code>website</code> directory.</p>

<p>Access the website at: http://127.0.0.1:5000/ via any web browser.</p>

<p>Admin users can access the CRUD dashboard at: http://127.0.0.1:5000/admin/home after configuring credentials (username & password) in the <code>__init__.py</code> file.</p>
