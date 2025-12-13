---
title: "Pokemon Type Effectiveness Calculator"
description: "Pokemon tends to attract a younger audience due to the simplicity of the story and mechanics: gather a team of 6 magical creatures to battle your way through the region and become champion. I was inspired to build a simple, quick, and easy web app that would allow even children to be able to understand how to use it"
image: "./pokemon-calc.png"
startDate: "2025-09-03"
endDate: "2025-10-03"
skills: ["TypeScript", "JavaScript", "CSS3", "HTML5", "Vite"]
# sourceLink: "https://github.com/lauroguedes/mary-ui-starter-kit"
demoLink: "https://elemental-draco.github.io/pokemon-type-calc/"
---

## About Pokémon Damage Type Calculator

The Pokémon Damage Type Calculator is an interactive web tool built to help players quickly determine type effectiveness for any attacking and defending Pokémon type combination. Designed as a clean, lightweight, and educational project, it provides instant feedback using accurate multiplier data and an intuitive user interface.

This project showcases strong front-end engineering fundamentals, including structured data modeling in JavaScript, dynamic rendering, and clean interaction patterns.



## Core Features

### Accurate Type Matchup Calculations
- **Real Type Multipliers**: Based on the official Pokémon type chart  
- **Instant Results**: Automatically calculates damage multipliers on selection  
- **Dual-Type Support**: Handles all single- and dual-type matchups  
- **Clear Output**: Displays effectiveness phrased as *Super Effective*, *Not Very Effective*, *Immune*, or standard damage

### Interactive UI
- **Two Dropdown Inputs**: Choose any attacker type and one or two defender types  
- **Auto-Updated Results**: No page reloads — updates with every change  
- **Color-Coded Feedback**: Visual clarity for different damage outcomes (optional design flair)  
- **Clean Layout**: Simple, readable interface for quick reference

### Structured Data Modeling
- **Type Objects**: Organized TypeScript data structure storing each type’s weaknesses, resistances, and immunities  
- **Reusable Logic**: A single calculation engine handles all combinations  
- **Modular Functions**: Separation of input handling, calculation, and rendering for maintainable code



## Technical Architecture

### Frontend Stack
Built entirely on lightweight, accessible technologies:
- **HTML5 & CSS3** for structure and styling  
- **JavaScript (ES6)** for all logic and interaction  
- **No Frameworks Required** — fast, dependency-free implementation  

### Core Implementation Highlights
- **Custom Type Data Model** using plain JavaScript objects  
- **Dynamic DOM Rendering** for result outputs  
- **Switch-Based or Map-Based Logic** for combining multipliers  
- **Mathematical Accuracy** through sequential multiplier evaluation  
- **Scalable Design** allowing easy additions (e.g., STAB, weather, abilities)


## User Experience

- Minimalist design focused on clarity and speed  
- Instant feedback with no clutter or confusing UI elements  
- Clear descriptions for effectiveness categories  
- Optional color coding for accessibility and faster scanning  
- Fully responsive layout suitable for desktop and mobile



## Purpose & Impact

The Pokémon Damage Type Calculator serves as a practical, educational reference for players while demonstrating the developer’s grasp of:

- Data organization and modeling  
- Problem decomposition and modular architecture  
- Interactive UI building  
- Mathematical logic and conditional evaluation  
- Clean, readable JavaScript code  

The project highlights the ability to transform a complex ruleset into an intuitive, reliable tool — making it an excellent portfolio piece for showcasing applied logic, user-focused design, and clean engineering skills.