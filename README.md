# Tailwind test with Node.js and Express.js
### 1. Generate css
terminal: `npm run biuld:css` 

- generates css into public/stylesheets/style.css
- repeat this step every time a new tailwind class or modification has been introduced

### 2. Run application
terminal: `npm start` 

- check localhost:3000
- no need to restart application when "client side" changes happened (inside ejs files)
- need to restart application when "server side" changes happened (in route files)

## How to use "links"
- links are found in the routes folder
- can be grouped by category, optional (e.g.: onboarding related links)

## How to use views
- views are located in the views folder
- `.ejs` files
- https://ejs.co/
