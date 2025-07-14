# AI-Powered E-Commerce

AI-Powered E-Commerce is a responsive, modern shopping experience showcasing AI-driven product recommendations and Stripe payment integration. This project serves as a portfolio piece by **Aalok Mandal (akm164)** to demonstrate front-end expertise, UI design skills, and basic AI concepts.

---

## Table of Contents

1. [Features](#features)  
2. [Technologies](#technologies)  
3. [Installation](#installation)  
4. [Usage](#usage)  
5. [Project Structure](#project-structure)  
6. [Future Improvements](#future-improvements)  
7. [About the Developer](#about-the-developer)  
8. [License](#license)  

---

## Features

- AI-Powered Recommendations with “AI Pick” badges and mock TensorFlow logic  
- Mobile-first, responsive layout styled with Tailwind CSS and Font Awesome  
- Product catalog with category filtering and sorting options  
- Shopping cart with add, update quantity, and remove functionality  
- Live subtotal and total price updates  
- Secure Stripe payment modal using Stripe.js and Elements  
- Interactive modals for cart, payment, and order confirmation  
- Toast notifications for cart actions  

---

## Technologies

| Category        | Tools & Libraries                             |
| --------------- | ---------------------------------------------- |
| Front-end       | HTML5, CSS3, JavaScript (ES6+)                |
| Styling         | Tailwind CSS, Font Awesome Icons              |
| AI Simulation   | TensorFlow (client-side mock recommendations) |
| Payments        | Stripe.js, Stripe Elements                    |
| Hosting         | Static server (e.g., serve, GitHub Pages)      |
| Version Control | Git, GitHub                                    |

---

## Installation
```
1. Clone the repository  
  git clone https://github.com/akm164/AI-Powered-Ecommerce.git

2. Change into the project directory
  cd AI-Powered-Ecommerce

3. Serve the app locally:
    - Using serve (recommended):
        npm install -g serve
        serve .
    - Or open index.html directly in your browser
```

## Usage
```
Launch the app in your browser or via your local server.
View the hero section to navigate quickly to products or learn more.
Scroll to Recommended For You for AI-driven product picks.
Browse Our Products, filter by category, or sort by price/popularity.
Click Add to Cart to include items in your shopping cart.
Open the cart modal to adjust quantities, remove items, or view totals.
Proceed to Checkout to open the Stripe payment modal (test mode).
Complete payment with test card details to see the order confirmation.
```

## Project Structure
```
AI-Powered-Ecommerce/
├── index.html           # Main HTML with layout, styles, and scripts
├── README.md            # Project documentation
├── assets/              # Images and static media (I am working on It) 
├── css/                 # Tailwind configuration and custom styles (I am working on It)
├── js/                  # JavaScript logic and modules (I am working on It)
└── LICENSE              # MIT License
```

## Future Improvements
```
Implement a real Node.js/Express backend with a database
Replace mock recommendations with a live TensorFlow microservice
Add user authentication and profile management
Persist cart state via localStorage or server-side sessions
Enhance accessibility and UI animations
```

## About the Developer
```
Aalok Mandal (akm164) Bachelor of Computer Science (Software Engineering and AI & Big Data) University of Wollongong
This project highlights my ability to build interactive, responsive web interfaces, integrate third-party APIs, and simulate AI-driven features in a front-end context.
Portfolio: https://akm164.github.io/My3DWebsite/
LinkedIn: www.linkedin.com/in/aalok-mandal-a80a8536b
Email: aalokm875@gmail.com
```

## License
```
This project is licensed under the MIT License. See the LICENSE file for details.
