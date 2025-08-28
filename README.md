# ONLINE_TICKETING_SYSTEM_RESPONSIVE_USING_HTML_CSS__JAVASCRIPTS

# Flight - Online Tour & Travel Ticketing System

This repository contains a responsive front-end template for a "Flight Tour and Travel" website. It is built using HTML, CSS, and JavaScript, and provides a modern, feature-rich user interface for an online ticketing system or travel agency portal. The template is designed to be visually appealing and easy for users to navigate, featuring sections for booking tickets, checking weather, exploring destinations, and finding recommended hotels.

## Features

-   **Responsive Design:** The layout is fully responsive and adapts to various screen sizes, from mobile devices to desktops.
-   **Ticket Booking Form:** An interactive form allows users to:
    -   Select 'From' and 'To' locations from a dropdown menu.
    -   Choose departure and return dates using a datepicker.
    -   Select trip type (Round trip or One-way).
-   **Weather Information:** A tabbed section to display the 5-day weather forecast for different destinations.
-   **Recommended Hotels:** A dynamic section showcasing recommended hotels with:
    -   A vertical tabbed navigation for different services (Living Room, Suite Room, Pool, etc.).
    -   An embedded YouTube video.
    -   An Owl Carousel image slider for suite rooms.
-   **Most Visited Places:** An Owl Carousel slider to display popular tourist spots with images and location names.
-   **Contact Page:** A dedicated contact page `contact.html` which includes:
    -   Contact information section.
    -   A functional-looking contact form.
    -   An embedded Google Map.
-   **Social Media Integration:** Links to various social media platforms like Facebook, YouTube, and Instagram.

## Technologies Used

-   **HTML5**
-   **CSS3**
-   **Frameworks & Libraries:**
    -   [Bootstrap v3.3.1](https://getbootstrap.com/)
    -   [jQuery v1.11.2](https://jquery.com/)
    -   [FontAwesome 4.7.0](http://fontawesome.io/)
    -   [Owl Carousel](https://owlcarousel2.github.io/OwlCarousel2/) for sliders.
    -   [Bootstrap Datepicker](https://github.com/uxsolutions/bootstrap-datepicker) for calendar inputs.
    -   Mixitup for filtering.

## Getting Started

This is a static website template. No special installation or build process is required.

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/kundankumar24/ONLINE_TICKETING_SYSTEM_RESPONSIVE_USING_HTML_CSS__JAVASCRIPTS.git
    ```
2.  **Navigate to the project directory:**
    ```sh
    cd ONLINE_TICKETING_SYSTEM_RESPONSIVE_USING_HTML_CSS__JAVASCRIPTS/flight/
    ```
3.  **Open the website:**
    Open the `index.html` file in your preferred web browser.

## File Structure

The project files are organized as follows:

```
flight/
├── css/              # All stylesheets
│   ├── bootstrap.css
│   ├── fontAwesome.css
│   ├── owl-carousel.css
│   └── tooplate-style.css  # Main custom styles
├── fonts/            # Web fonts (FontAwesome, Glyphicons)
├── img/              # All images used in the template
├── js/               # JavaScript files
│   ├── bootstrap.js
│   ├── datepicker.js
│   ├── owl.carousel.min.js
│   ├── main.js       # Custom script for initializations and interactions
│   └── plugins.js    # Additional plugins like lightbox and mixitup
├── index.html        # The main landing page
└── contact.html      # The contact page
```

Customization

-   **Content:** All text and content can be modified by editing the `index.html` and `contact.html` files.
-   **Images:** Replace the images in the `img/` directory with your own. Ensure the new images have the same dimensions or adjust the CSS accordingly.
-   **Styling:** Custom styles can be modified in `css/tooplate-style.css`.
-   **Map:** To change the location on the contact page map, update the `src` attribute of the `iframe` in `contact.html` with your own Google Maps embed URL, as indicated by the comment in the file.
-   **Booking Form:** The dropdown locations in the booking form can be updated by editing the `<option>` tags within the `<select>` elements in `index.html`.

## Credits

This template is based on the "Flight" template from [tooplate.com](http://www.tooplate.com/view/2093-flight) and also credits [Code Projects](http://www.code-projects.org) in the footer.
