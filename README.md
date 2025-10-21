# My Virtual Pet

**First Project Statement: Website Development**  
**Published:** October 20, 2025  
**Author:** Shannon Douglas  
**Class / Assignment:** Website Development / Assignment 1

---

## Project Overview
*My Virtual Pet* is an interactive web application that allows users to adopt and care for a virtual pet. It also educates them about pet care, different types of animals, habitats and environments, and fun facts on the pet they adopt. There is a link to an informative website as well. Users can feed, cuddle, and play with their pet while managing resources like food, treats, and toys. The project demonstrates responsive design, interactive UI elements, and multimedia integration (audio for pet reactions). The site is fully functional on both desktop and mobile devices.

---

## Technologies Used
- **Languages:** HTML, CSS, JavaScript  
- **Tools:** VS Code, LocalStorage for data persistence, Audio API for sounds  
- **Design:** Responsive layout with Flexbox, media queries for mobile, interactive buttons  

---

## Pages & Functionality

### 1. `index.html`
**Purpose:** Landing page for the website to introduce the user and allow navigation.  
**Functions:**
- Navigate to different pages.

---

### 2. `shelter.html`
**Purpose:** Where the user adopts their pet.  
**Functions:**
- Browse the four different pets.
- Select a pet and get redirected to `pet.html`.

---

### 3. `pet.html`
**Purpose:** Interact with the chosen pet by feeding, cuddling, or having them do tricks. Each action increases the pet’s “battery” levels so it isn’t sad.  
**Functions:**
- **Feed your pet:** Give food to increase the hunger level.  
- **Cuddle your pet:** Give treats to increase the happiness level.  
- **Do a trick!:** Give toys to increase the boredom level. Audio relevant to the animal type plays.

---

### 4. `store.html`
**Purpose:** Buy food, toys, and treats to engage with the pet on `pet.html`.  
**Functions:**
- Purchase three different products with a starting budget of $80.  
- Track current inventory at the bottom of the page.  
- Users cannot purchase once they run out of money.

---

## Specific Notes on Functionality
- Visiting `pet.html` before selecting a pet on `shelter.html` displays a placeholder pet image and instructions to adopt a pet.  
- Selecting a new pet resets all variables, including the budget in `store.html` back to $80.  
- When a pet performs a trick, audio relevant to the animal type plays.  
- Pets start in a "sad" state and display three different reactions for each action on `pet.html`.  
- The website layout is responsive for mobile screens and maintains a clean, user-friendly interface.

---

## User Flow
1. Navigate to `shelter.html` to adopt a pet.  
2. Visit `pet.html` to interact with the pet (feed, cuddle, or play a trick).  
3. Use `store.html` to purchase items for the pet.  
4. Watch the pet react visually and audibly based on actions.

---

## Possible Future Enhancements
- Add more pets with unique behaviors.  
- Implement animations when pets perform tricks.  
- Add a scoring or achievement system to gamify interactions.  
- Include additional multimedia (videos, interactive sounds).
