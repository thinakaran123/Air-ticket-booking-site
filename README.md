
## Flight Booking & Management Web Application
This project is a multi-page, responsive web application designed for flight searching, ticket booking, and real-time flight status tracking. It features a dynamic frontend built with HTML5, CSS3 (Bootstrap 5), and JavaScript (jQuery).

## Project Structure
To maintain industry standards, the project is organized into logical directories:
Root Directory: Contains main HTML files (index.html, tb.html, cyf.html, finalp.html, thanku.html).
assets/css/: Custom stylesheets for different modules (style.css, tb.css, cyf.css, finalp.css).
assets/images/: Local branding assets including airline logos (IndiGo, SpiceJet, Air India, Vistara, Air Asia, Go First).
src/: Background images and payment-related bank icons.

## Key Features
1. Flight Status Dashboard (index.html)
Displays a list of available flights in a responsive table.
Dynamic Data: Uses custom JavaScript to randomize flight numbers, airlines, routes, and timings upon page load to simulate updates.

2. Ticket Booking System (tb.html)
Trip Options: Support for both "One Way" and "Round Trip" selections.
Route Swap: A convenience feature allowing users to instantly swap "From" and "To" destinations with a single click.
Flight Search: Validates user input before displaying a list of available airline fares.

3. Check Your Flight (cyf.html)
Provides two search methods: Search by Flight Number or Search by Route.
Interactive Popups: Displays detailed flight information in a modal window upon successful search.

4. Passenger Details & Secure Payment (finalp.html)
Dynamic Member Addition: Users can add multiple passengers; the system dynamically generates input fields for names, age, and gender.
Trip Assurance: Optional travel insurance selection.

Multiple Payment Gateways: Supports simulated payments via Credit Card, Net Banking, and Payoneer.


Security Simulation: Includes a mock OTP (One Time Password) verification flow for all payment methods.

🛠️ Technical Stack

Frontend: HTML5, Bootstrap 5.2.3 (for grid system and responsiveness).
Styling: Custom CSS3 with heavy use of Media Queries for mobile optimization.
Scripting: JavaScript & jQuery 3.6.4 for DOM manipulation, form validation, and event handling.
Icons: Integrated via Icons8 CDN for a modern UI.

📝 Setup Instructions
Clone the repository to your local machine.
Ensure your file structure matches the Project Structure section above to maintain link integrity.
Open index.html in any modern web browser.


Note: An active internet connection is required to load Bootstrap, jQuery, and external icons.
