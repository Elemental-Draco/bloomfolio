---
title: "PokePlushes"
description: "PokePlushes is a lightweight e-commerce-style web application that showcases a collection of Pokémon-themed plush toys."
image: "./pokeplushes.png"
startDate: "2025-07-01"
endDate: "2025-08-01"
skills: ["HTML5", "CSS3", "JavaScript"]
demoLink: "https://elemental-draco.github.io/PokePlushes/"
---

## About PokePlushes

PokePlushes is a lightweight e-commerce-style web application that showcases a collection of Pokémon-themed plush toys. Built as a practical front-end project, it focuses heavily on cart management, quantity updates, and dynamic pricing. The main goal of the project is to demonstrate shopping cart functionality using clean JavaScript logic and real UX patterns seen in modern online stores.

---

## Core Features

### Shopping Cart Functionality
- **Add to Cart**: Users can add any plush directly from the product listing  
- **Quantity Handling**: Automatically increases quantity if an item already exists in the cart  
- **Remove Items**: Users can remove individual products or clear the entire cart  
- **Real-Time Updates**: Cart contents, item count, and total price update instantly without page reloads  
- **Persistent Cart**: Uses `localStorage` so items remain saved even after page refresh or browser close  

### Price & Quantity Calculations
- **Dynamic Subtotals**: Each item displays a running subtotal based on its current quantity  
- **Accurate Total Price**: Automatically recalculated on every update  
- **Input-Safe Logic**: Prevents negative quantities, malformed inputs, or invalid states  
- **Cart Badge Indicator**: Shows the total number of items in the cart at all times  

### Product Display & Inventory
- **Product Data Structure**: Stores item names, images, prices, IDs, and descriptions in a clean JS array/object format  
- **Auto-Rendered Products**: JavaScript loops generate the product list dynamically from data  
- **Consistent Item Cards**: Displays name, image, price, and Add to Cart button  

---

## Technical Architecture

### Frontend Stack
Built using modern, dependency-free front-end tools:
- **HTML5 & CSS3** for layout and styling  
- **JavaScript (ES6)** for all cart logic and rendering    
- **No external frameworks required**, making the app fast and simple to deploy  

### Core Implementation Highlights
- **Modular Functions** for adding items, removing them, updating quantities, and recalculating totals  
- **Cart State Object** stored centrally for predictable updates  
- **Event Delegation** used for handling add/remove/update buttons efficiently  
- **Serialization** of cart data for persistence across sessions  
- **DOM Updating Logic** separated from calculation logic for cleaner code  

---

## User Experience

- Easy-to-scan product grid with clear pricing  
- Immediate cart updates for a snappy, responsive feel  
- Simple quantity controls for adjusting cart items  
- Persistent cart that makes the shopping experience feel realistic  
- Functional design focused entirely on usability and interaction rather than visual complexity  

---

## Purpose & Impact

PokePlushes serves as a practical demonstration of real e-commerce logic and front-end application structure. Through this project, users can:

- Browse products in a familiar shopping layout  
- Add items to a cart and adjust quantities intuitively  
- See accurate totals and cart updates in real time  


For employers, the project highlights:
- Strong JavaScript fundamentals  
- Practical understanding of shopping cart logic  
- Data modeling and DOM manipulation  
- State management without frameworks  
- Real-world, resume-relevant e-commerce patterns  