# Le Rendez-vous | Restaurant Menu Page

This project is a **simple restaurant menu webpage** built to demonstrate the use of **HTML** and **CSS selectors** for styling and interactivity.  

The menu displays different food categories (Starters, Main Courses, Desserts, Beverages), each with styled dish names, descriptions, and prices. Special dishes and spicy dishes are highlighted. Images are included for a more appealing design.

---



## Project Structure

/menu-project
│── index.html # Main HTML file
│── styles.css # Styling file (CSS)
│── /images # Contains food category images
│── README.md # Documentation


---


## Languages Used
- **HTML5** – Structure of the webpage.
- **CSS3** – Styling, layout, selectors, and interactivity.

---


## HTML Structure

### Key Elements:
- `<header>` → Page title and subtitle.  
- `<section>` → Each menu category (Starters, Mains, Desserts, Beverages).  
- `<ul> / <li>` → Menu unordered lists with dishes and descriptions.  
- `<span>` → Used for separating **dish names** (`.dish`) and **prices** (`.price`).  
- `<img>` → Category images (`.img`).  
- `<footer>` → Copyright.  

### Special Markup:
- `.special` → Highlights recommended/chef’s choice/special dishes.  
- `.spicy` → Highlights spicy dishes with distinct red color.  

---


## CSS Styling

### Selectors Used:
1. **Universal Selector** → 
`* { box-sizing: border-box; margin: 0; padding: 0; }`  
   - Ensures consistent styling and reset across the page.  

2. **Element Selectors** → e.g. `h1`, `h2`, `h3`, `li`, `ul`, `footer`  
   - Styles headings, lists, and layout.  

3. **Class Selectors** →  
   - `.menu-section` → Styles each section container.  
   - `.dish` → Styles dish names.  
   - `.price` → Styles and aligns prices to the right.  
   - `.special` → Highlights special dishes.  
   - `.spicy` → Colors spicy dishes red.  
   - `.img` → Styles images for each category.  

4. **ID Selectors** → `#starters`, `#mains`, `#desserts`, `#beverages`  
   - Identify specific sections of the menu.  

5. **Descendant Selectors** → `header h1`, `.menu-section ul li`  
   - Target nested elements.  

6. **Pseudo-class Selectors** → `li:hover`  
   - Adds hover effects for interactivity (highlight + slight scale-up).  


---


## 📝 Summary
This project demonstrates the practical use of **HTML elements** and **CSS selectors** to build a **user-friendly, interactive restaurant menu webpage**. It highlights:  
- The importance of semantic HTML structure.  
- Applying a variety of CSS selectors.  
- Designing for readability and aesthetics.  
- Incorporating interactivity with hover effects.  

---

© 2024 Le Rendez-vous. All rights reserved.