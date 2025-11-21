# Cafe Ordering System

> Flask, Python,  SQLAlchemy, HTML, CSS, Bootstrap, JavaScript, Jinja

## Overview
* Mobile-friendly cafe ordering system built with a Flask/Python backend
* Customizable drink options, search filters, and business hours restrictions
* Admin dashboard for managing the cafe database (WIP)
* Hosted on PythonAnywhere at: https://sunrightcafe.pythonanywhere.com

## 🔖 Table of Contents
* [Website Demo](https://github.com/jschhie/toast-tab-cafe/blob/main/README.md#website-demo)
* [Running the Website Manually](https://github.com/jschhie/toast-tab-cafe/blob/main/README.md#running-the-site-manually)

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

<hr>

## Running the Site Manually
1. Clone this repository:
```bash 
git clone https://github.com/jschhie/toast-tab-cafe.git [folderNameHere]
```

2. Navigate into the folder: 
```bash 
cd [folderNameHere]
```

3. Create and activate virtual environment (`venv`):
> To isolate the project's dependencies

```bash
python3 -m venv venv
source venv/bin/activate
```

4. Install the required packages:
```bash
pip3 install -r requirements.txt
```

5. Run the Flask app:
```bash
python3 main.py
```

<p>The application will automatically generate a <code>cafe_database.db</code> file in the <code>website</code> directory.</p>

<p>Access the website at: http://127.0.0.1:5000/ via any web browser.</p>

<p>Admin users can access the CRUD dashboard at: http://127.0.0.1:5000/admin/home after configuring credentials (username & password) in the <code>__init__.py</code> file.</p>
