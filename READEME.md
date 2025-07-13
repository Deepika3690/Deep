Smart Register Flask App

This is a simple inventory management and financial tracking application built with Flask, HTML, Tailwind CSS, and JavaScript. It allows users to add new items to inventory, view existing inventory, and modify stock quantities due to sales or damage, while also tracking profit and loss.

Features

Add New Items: Easily add items with unique IDs, names, quantities, and cost prices.

Inventory & Valuation View: See a comprehensive list of all inventory items, including total unique items, total quantity, and total inventory value.

Search Functionality: Quickly find items in the inventory using a search bar.

Stock Modification: Adjust item quantities for sales or damage, with automatic calculation of profit or loss.

Financial Summary: View a real-time summary of total profit and total loss.

Local Storage Persistence: All inventory and financial data are saved locally in the browser, persisting across sessions.

Responsive Design: The application is designed to be usable on various screen sizes. (mobile, tablet, desktop).

Project Structure

The project follows a standard Flask application structure:

app.py

requirements.txt

Procfile

-templates/

index.html

static/

-styles.css

script.js

app.py: The main Flask application file, handling routes and rendering templates.

requirements.txt: Lists Python dependencies for the project.

Procfile: Specifies the command to run the application on platforms like Render.

templates/: Contains HTML template files (e.g., index.html).
