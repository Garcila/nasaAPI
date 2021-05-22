# NASA API app 🚀

We'll go over the process of creating an application that gets images from NASA and displays them on the page alongside some relevant information.

## Main steps

- Create initial files
- Initialize git and create a GitHub repo
- Introduce the NASA API
  - [NASA](https://api.nasa.gov/)
  - [🌜 search](https://images.nasa.gov/search-results?q=moon&page=1&media=image)
- Get data from the API
- Introduce CSS Framework Bahunya
- Populate the page with desired data
- Add a form to select image type
- Use CSS variables to set colours
- Add dark/light mode with CSS and JS
- Deploy

### Detail

- Create index.html template
- Git it
- GitHub it
- HTML Populate initial index.html
  - header -> h1 title -> h2 subtitle
  - main ->
    - article
      - a form will be here
      - maybe some text
    - article -> placeholder to include images
  - add style and script tags and test them
- JavaScript
  - Explore Nasa API
  - Console log images
  - Create Function to get images
  - Create Function to populate page with images
- HTML
  - Create form to collect query
- JavaScript
  - Add event listener to capture input and run function
  - Add a button to change color mode
  - Select the button and store in variable
- CSS
  - Introduce Bahunya -classless
  - Add Bahunya
  - Work on the style tag to add
    - :root[color-mode='light']
    - :root[color-mode='dark']
    - var currentMode = html.getAttribute('color-mode');
    - use instructions in Bahunya to set colour
- Deploy GitHub and maybe Netlify or Vercel