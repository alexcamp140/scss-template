########### SCSS TEMPLATE ###########

**Introduction**: To utilize an SCSS template, you must have a tool to transpile SCSS to CSS. 

- **Create React App** supports SCSS transpilation out of the box.
- **Webpack**, configured with `css-loader`, can also handle SCSS.
- If you're not using these methods, you can transpile SCSS with Sass directly.

**Steps to Use Sass for Transpilation**:
1. **Install Node.js and npm**: Ensure you have Node.js and npm installed in your development environment.

2. **Install Sass Globally**:
   In the terminal, run the command:
        npm install -g sass

3. **Linking CSS in HTML**:
Ensure the `<link>` tag in your `index.html` targets the output CSS file, like so:
<link rel="stylesheet" href="output.css">

**Transpile SCSS to CSS:**
    Use the following commands in the terminal:

    To transpile once:
        sass assets/styles/index.scss output.css
    To enable continuous watching and transpilation (the CSS output file gets updated automatically after every save):
        sass --watch assets/styles/index.scss:output.css

    Remember to replace assets/styles/index.scss with the path to your main SCSS file, and output.css with your desired output CSS file path.

**Style**
   You can find many style for cards, buttons, menus, paragraph, ...


**Icons**
   In thisd template, you'll find icons. I use personnaly "font awesome". So you can use Font Awesome CDN to use this part.


