## 1) Simple horizontal navbar (desktop)

**Goals:** learn to properly list navigation links on a single line.  
**Constraints:** use `display: inline-block` or `display: inline`; no positioning allowed.  

**Instructions:**
* Create a navigation bar at the top with a text logo and 5 links.  
* Display the links side by side instead of stacked vertically.  
* Add some spacing between links (using margins for example).  
* Optionally separate links with a left border.  
* Add visible effects on `:hover` and `:focus` states.  

**Criteria:** links aligned neatly on one line, clear spacing, readable contrasts.  
**Bonus:** create a smooth underline animation using background-size and transition.

![exo 01- Navbar](assets/exo01.png)
---

## 2) “Hero” header section

**Goals:** manage width, rhythm, typography and button hierarchy.  
**Constraints:** no positioning.  

**Instructions:**
* Create a hero section with a main title, subtitle, paragraph and a call-to-action button.  
* Center the text horizontally using text alignment.  
* Limit the text width with a maximum width to keep it readable.  
* Style the button with clear colors and rounded corners.  
* Add visual effects on hover and focus.  

**Criteria:** comfortable reading, clear text hierarchy.  
**Bonus:** add a CSS gradient or a light background image.

![exo 02- Hero](assets/exo02.png)
---

## 3) Product cards (2–3 per row)

**Goals:** build reusable product cards.  
**Constraints:** use `display: inline-block`; no positioning.  

**Instructions:**
* Create 6 product cards, each containing an image, title, price and “Add” button.  
* Ensure all cards have equal width and consistent spacing.  
* Use inline-block and handle unwanted white space between cards.  
* Each card should have padding, rounded corners, and a light background.  

**Criteria:** consistent alignment and spacing.  
**Bonus:** add a small “Promo” or “New” badge without absolute positioning.

![exo 03- Produits](assets/exo03.png)
---

## 4) Accessible signup form

**Goals:** learn to style fields, labels and buttons accessibly.  
**Constraints:** no positioning; use `fieldset` and `legend` properly.  

**Instructions:**
* Create a form with a title and fields: name, email, password, consent checkbox, and submit button.  
* Each field should have a visible label.  
* Leave vertical space between input groups.  
* Make sure focus states are visible (when tabbing through fields).  
* Style the submit button to stand out.  

**Criteria:** readable layout, visible focus, proper form structure.  
**Bonus:** add short helper text under inputs (e.g. “8+ characters recommended”).

![exo 04- Formulaire](assets/exo04.png)
---

## 5) Pricing table

**Goals:** style a semantic table to present different offers.  
**Constraints:** use a real `<table>` element; no positioning or flex/grid.  

**Instructions:**
* Create a table with a header row and several offer rows.  
* Each column represents a plan (Basic, Pro, Business).  
* Style headers differently to stand out.  
* Alternate background colors for rows.  
* Highlight a row or column on hover.  
* Keep borders thin and consistent.  

**Criteria:** readable, structured layout.  
**Bonus:** visually highlight the “Recommended” plan using a color accent.

![exo 05- Tableau](assets/exo05.png)
---

## 6) Image + text block (“media object”)

**Goals:** place an image beside text without using flex or grid.  
**Constraints:** use floating and clearing (`float` + `overflow` or `clearfix`).  

**Instructions:**
* Create a block with an image and descriptive text.  
* The image should appear on the left, text on the right.  
* Include a title, paragraph, and button under the text.  
* Leave some space between the image and text.  
* On smaller screens, stack the text under the image.  

**Criteria:** clean alignment, readable on all screen sizes.  
**Bonus:** add small icons before each paragraph using pseudo-elements.

![exo 06- Image](assets/exo06.png)
---

## 7) Multi-column footer

**Goals:** structure a footer area with multiple sections.  
**Constraints:** use inline-blocks or floats; no positioning.  

**Instructions:**
* Create a footer with a different background color from the page.  
* Add 3 or 4 sections: “About”, “Useful Links”, “Contact”, “Socials”.  
* Each section should have a heading and a list of links or text.  
* Display the columns side by side.  
* Add padding inside and around columns for spacing.  
* Ensure text is readable on a dark background.  

**Criteria:** clean column alignment, consistent spacing.  
**Bonus:** add a decorative top border or gradient.

![exo 07- Footer](assets/exo07.png)
---

## 8) Breadcrumbs & Pagination

**Goals:** build two types of simple navigation.  
**Constraints:** use inline or inline-block; no positioning.  

**Instructions:**
* Create a breadcrumb trail: “Home > Shop > Product”.  
* Each step is clickable except the last one.  
* Add separators between items (like “>”).  
* Below, add pagination links: 1, 2, 3, Next, Previous.  
* The current page should have a distinct style.  
* Add hover and focus states on links.  

**Criteria:** clear navigation, consistent spacing and alignment.  
**Bonus:** use `aria-current="page"` for accessibility.
![exo 08- Ariane](assets/exo08.png)
---

## 9) FAQ accordion (CSS-only)

**Goals:** create an interactive accordion without JavaScript.  
**Constraints:** no positioning; use `<details>` and `<summary>` or `:checked`.  

**Instructions:**
* Create 5–6 questions.  
* Each question reveals an answer when opened.  
* Use built-in elements or CSS toggles to control visibility.  
* Style questions with bold text and maybe an icon.  
* Add smooth opening and closing transitions.  

**Criteria:** readable layout, smooth interaction, keyboard-friendly.  
**Bonus:** animate the icon rotation or change color on open/close.

![exo 09- FAQ](assets/exo09.png)
---

## 10) Responsive navbar with CSS toggle

**Goals:** make a responsive navbar that works on mobile without absolute positioning.  
**Constraints:** no positioning; use checkbox or `<details>` trick.  

**Instructions:**
* Reuse your first navbar structure.  
* Add a checkbox or toggle button to show/hide the menu on mobile.  
* On desktop: links visible in a horizontal line.  
* On mobile: menu hidden by default, visible when toggled.  
* Add simple transitions for the opening/closing effect.  
* Keep the navigation accessible via keyboard.  

**Criteria:** smooth behavior on all screens, no overflow issues.  
**Bonus:** create a “hamburger” icon in pure CSS (three lines turning into an X).

![exo 10- Navbar Toggle](assets/exo10.png)
![exo 10- Navbar Toggle](assets/exo10_2.png)

## Graphic charter

 ### Colors
  * --bg: #ecf7f5;
  *  --muted: #e8f1ef;
  * --text: #0f1b1a;
  * --text-soft: #425a58;
  * --primary: #0f766e;
  * --primary-700: #0c5f59;
  * --primary-100: #e0f2f1;
  * --accent: #22c5ac;
  * --warning: #f59e0b;
  * --radius: 16px;
  * --shadow: 0 6px 18px rgba(15, 118, 110, 0.1);

### Fonts
  * font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto,"Helvetica Neue", Arial, sans-serif;

