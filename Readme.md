# GoCar Jayamahe

[![License](https://img.shields.io/badge/License-MIT-blue)](LICENSE)

This repository contains the code for the **GoCar Jayamahe** project. It is a web application built using **HTML**, **CSS**, **JavaScript**, and **Bootstrap**. The application is designed to provide users with an easy-to-use platform for booking car rentals.

## Features

- **Responsive Design**: Built with Bootstrap to ensure compatibility across all devices.
- **Car Rental Booking**: Allows users to book various types of vehicles (e.g., Toyota Innova).
- **Real-Time Availability**: View and book available cars based on schedule and location.
- **User-Friendly Interface**: Easy-to-navigate design with clear call-to-action buttons.
- **Interactive Map Integration**: Locate the car rental stations or vehicle pick-up points.
- **Booking Confirmation**: Instant confirmation after a successful booking.

## Installation

To get started with this project, follow the steps below to run it locally on your machine:

1. Clone this repository:
    ```bash
    git clone https://github.com/NuricoVicyyanto/gocar-jayamahe.git
    ```

2. Navigate to the project folder:
    ```bash
    cd gocar-jayamahe
    ```

3. Open the `index.html` file in your preferred web browser:
    ```bash
    open index.html
    ```

   Or, if you prefer to run it on a local server:
    - You can use a simple local server (e.g., Python's HTTP server or any other server) to view the site locally.

   Example with Python 3:
    ```bash
    python3 -m http.server
    ```

4. Access the app by navigating to `http://localhost:8000` in your browser.

## Usage

Once you've opened the project in your browser, you can interact with the booking system. Here are some of the key interactions:

- **Selecting a Car**: Choose the vehicle you want to rent, see its availability, and choose the rental period.
- **Location Selector**: Select your preferred car pick-up and drop-off locations.
- **Booking Confirmation**: After filling in the necessary details, confirm your booking and get a summary of your reservation.

## Technologies Used

- **HTML**: For the basic structure of the application.
- **CSS**: For styling the layout and components.
- **JavaScript**: For interactive elements such as the booking form and real-time availability checking.
- **Bootstrap**: For a responsive and modern design.
- **jQuery**: For handling some dynamic elements (if applicable).

## Resources for Learning Web Development

If you're new to web development or want to improve your skills, here are some helpful resources:

- [HTML5 Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [CSS3 Documentation](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [JavaScript Documentation](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
- [Bootstrap Documentation](https://getbootstrap.com/)
- [jQuery Documentation](https://jquery.com/)

## Contributing

If you would like to contribute to this project, follow these steps:

1. Fork this repository
2. Create a new branch (`git checkout -b new-feature`)
3. Commit your changes (`git commit -am 'Add new feature'`)
4. Push to the branch (`git push origin new-feature`)
5. Create a pull request

We welcome contributions to improve the GoCar Jayamahe project, whether it's bug fixes, adding new features, or enhancing the user interface.

## FAQ

### How do I deploy this project to a live server?
To deploy this project to a live server, you will need to host the HTML, CSS, JavaScript, and other assets on a web server. Services like [Netlify](https://www.netlify.com/), [GitHub Pages](https://pages.github.com/), or [Vercel](https://vercel.com/) are good choices for static websites.

### Can I customize the car options and booking process?
Yes, you can modify the car options, availability, pricing, and the booking process. Look for the corresponding sections in the JavaScript files, particularly for availability checking and booking logic.

### Is there a backend for this application?
No, this project is currently a front-end application with static data. For full functionality (e.g., real-time availability and bookings), you would need to integrate a backend or API.

## License

This project is licensed under the [MIT](LICENSE) License.
