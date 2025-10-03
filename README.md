# QR Code Menu Tool for Restaurants

A Django‑based web application that enables restaurants to generate QR codes linking to digital menus. Diners can scan the QR code to view the menu on their devices — no printed menus required.

---

##  Features

- Create and manage restaurant menus (categories, items, prices, descriptions).  
- Dynamically generate a QR code that links to a public menu view.  
- Template-based menu display (HTML) for mobile and web browsers.  
- Easy to deploy and configure with minimal dependencies.  

---

## Usage

Log in via the Django admin (or via whatever UI you build)

Create menu categories and menu items (with names, description, prices)

The system will generate a QR code URL for your restaurant menu

Place the QR code in printed material (table tents, flyers, etc.)

Customers scan the code and are taken to the menu page

## Technologies Used

Python 3.x

Django Web Framework

SQLite (default database)

Pillow (for image uploads)

qrcode (for generating QR codes)

HTML/CSS (Django templates)

## Future Improvements

Multi-restaurant support

Enhanced UI/UX

QR scan analytics

Custom branding/themes

Menu translations (multi-language)


