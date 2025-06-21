# Star Wars Character Explorer

A simple, interactive web application that allows users to explore characters from the Star Wars universe. With the click of a button, the application fetches and displays detailed information and an image for a random character.

## Features

* **Random Character Discovery:** Fetches a random Star Wars character from the API.

* **Detailed Information:** Displays comprehensive data for each character, including their species, gender, height, homeworld, affiliations, and more.

* **Categorized Display:** Organizes character details into logical sections like General, Appearance, Biography, and Allegiance for easy reading.

* **Visuals:** Shows an image for each character.

* **Responsive Design:** The interface is designed to work well on both desktop and mobile devices.

* **Sleek Interface:** Features a dark, space-themed design with glowing buttons and smooth animations.

## How to Use

1. Open the `index.html` file in a web browser.

2. Click the **"Get Random Character"** button.

3. A loading spinner will appear while the data is being fetched.

4. A card will appear displaying the image and detailed information for a random character.

5. To see another character, click the **"Get Another Character"** button at the bottom of the card.

## Technologies Used

* **HTML5:** The structure of the web page.

* **Tailwind CSS:** A utility-first CSS framework for styling the application.

* **JavaScript (ES6+):** For fetching data from the API and dynamically updating the content on the page.

* **Fetch API:** Used for making asynchronous network requests to the Star Wars API.

## API Used

This project uses the open-source [Star Wars API by Akabab](https://github.com/akabab/starwars-api), which provides comprehensive data and images for characters from the Star Wars universe.

**API Endpoint:** `https://rawcdn.githack.com/akabab/starwars-api/0.2.1/api/all.json`
