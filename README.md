# React Pricing Cards Component

A responsive and dynamic pricing card component built with React. This project demonstrates component-based architecture by separating UI logic from data, mapping through arrays to render elements dynamically, and applying conditional styling.

##  Features

* **Dynamic Data Rendering:** Uses the `.map()` method to generate pricing cards from a centralized data array.
* **Conditional Styling & Icons:** Dynamically renders FontAwesome tick (`fa-check`) or cross (`fa-x`) icons and grays out text based on feature availability.
* **Fully Responsive:** Adapts seamlessly to desktop, tablet, and mobile screens using CSS media queries.
* **Interactive UI:** Smooth transition effects, including a slight upward lift and enhanced box-shadow when hovering over the cards.
* **Clean Project Structure:** Separation of concerns with dedicated folders for components and mock data.

##  Technologies Used

* **Frontend:** React (Functional Components, Props)
* **Build Tool:** Vite
* **Styling:** CSS3 (Flexbox, Transitions, Hover States)
* **Icons:** FontAwesome (via CDN)
* **Fonts:** Open Sans (Google Fonts)

## Project Structure

```text
src/
├── components/
│   └── PricingCard.jsx    # The individual card component
├── data/
│   └── pricingData.js     # The array of pricing tier objects
├── App.jsx                # Main container mapping the data
├── App.css                # Styling, responsiveness, and hover effects
└── main.jsx               # React entry point
