# Frontend Mentor - Social Links Profile Solution

This is a solution to the [Social Links Profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.  

## Table of Contents

  - [The Challenge](#the-challenge)  
  - [Links](#links)  
  - [Built With](#built-with)  
  - [What I Learned](#what-i-learned)  
  - [Author](#author)  

---

### The Challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page.  
- View a clean, responsive social links profile card.  
- Have the layout adapt for mobile screens (mobile-first approach).  

### Links

- Solution URL: [GITHUB REPO](https://github.com/noob-coder6/Social-Links-Profile.git)  
- Live Site URL: [Live Site](https://noob-coder6.github.io/Social-Links-Profile/)  

---

### Built With

- HTML5 semantic markup  
- CSS3 (Flexbox, CSS variables, mobile-first workflow)  
- Google Fonts (Inter)  
- Claude AI
- Gemini Code Assist

### What I Learned

During this project, I practiced:

- Creating a **responsive card layout** using Flexbox and custom CSS variables.  
- Styling hover and focus states for interactive links.  
- Using semantic HTML for accessibility . 

Example CSS snippet I’m proud of:

```css
.profile-card__links a {
  display: block;
  background-color: var(--neutral-grey);
  color: var(--neutral-white);
  text-decoration: none;
  font-weight: 700;
  padding: 12px;
  border-radius: 8px;
  transition: background-color 0.3s ease, color 0.3s ease;
}

.profile-card__links a:hover,
.profile-card__links a:focus {
  background-color: var(--primary-green);
  color: var(--neutral-off-black);
  outline: none;
} 
```

## Author

- Frontend Mentor - [@noob-coder6](https://www.frontendmentor.io/profile/noob-coder6)


To be notes that the profiles do not really redirect to the sites 
