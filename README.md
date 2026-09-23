# GoFit

A health and fitness website in Portuguese. The home page links to the site's sections, and the nutrition page covers macro vs. micronutrients, how to read nutrition labels, types of diets and mental health. It also has a daily calorie calculator (Harris-Benedict formula, adjusted for activity level and goal), flip cards and a "fact or myth" quiz. There's also an "about us" page.

The Academia and Calculadoras pages are linked in the nav but don't exist yet.

**Live:** https://gofit-oficial.vercel.app

## Stack

- HTML5
- CSS3 (with a separate stylesheet for responsive layout)
- Vanilla JavaScript: calorie calculator, fact/myth quiz, flip cards, dropdown and hamburger menu

## Running locally

No build step - open `index.html` in a browser, or serve the folder:

```bash
python -m http.server 8000
```

Then go to http://localhost:8000.

## Structure

```
index.html          # home
nutricao.html       # nutrition content, calorie calculator, fact/myth quiz
quemsomos.html      # about us
style.css, resposivo.css
calcCaloria.js      # daily calorie calculator
fato-mito.js        # fact or myth quiz
flip-card.js, drop-menu.js, menu-hamburguer.js, script.js
img/
```
