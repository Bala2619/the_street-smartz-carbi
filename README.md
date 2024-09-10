# Carbi Vehicle Browser Website

## Project Overview:
Carbi is a web-based platform that allows users to browse and compare cars and bikes based on various criteria such as brand, body type, budget, and fuel type. The website includes a clean and intuitive user interface with powerful filtering options to help users make informed decisions when selecting vehicles.

## Key Features:
- **Browse Cars and Bikes**: Users can filter vehicles by brand, body type, fuel type, and budget.
- **Database-Driven**: The platform is backed by a database (MySQL) to store vehicle data and user information.
- **User Management**: Allows users to register and log in to personalize their experience.
- **Responsive Design**: Optimized for a variety of devices using HTML and CSS.
- **Dynamic Content**: PHP scripts manage server-side interactions, including retrieving vehicle data from the database.

## Technologies Used:
- **Frontend**: HTML, CSS
- **Backend**: PHP
- **Database**: MySQL (Schema provided in `carbi.sql`)
- **Images**: Includes various images for vehicles, brands, and user interface elements.

## Project Structure:
- `index.html`: Landing page.
- `bike.html`, `brand.html`, `fueltype.html`: Pages for browsing bikes and cars by different attributes.
- `php/`: Contains PHP scripts for handling server-side logic and database interaction.
- `carbi.sql`: Database schema for vehicles and users.
- `CSS/`: Stylesheets for different sections of the website.
- `images/`: Contains all image assets used in the website.

## Setup Instructions:
1. Clone this repository.
2. Import the `carbi.sql` file into your MySQL database.
3. Update the PHP files with your database connection details.
4. Launch the website by opening `index.html` in a web browser.

## License:
This project is licensed under the MIT License.
