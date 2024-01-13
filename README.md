# Theme-Based Portfolio Website

This is a theme-based portfolio website template designed using HTML and CSS. The template allows you to showcase your personal and professional information with a customizable theme.

## Features

- **Responsive Design:** The website is responsive and can be viewed on various devices, providing an optimal user experience.
  
- **Customizable Themes:** Easily switch between different themes to personalize the look and feel of your portfolio.

- **Portfolio Sections:** Organize and showcase your work, skills, education, and other relevant information in dedicated sections.

## Getting Started

1. Clone this repository to your local machine:

    ```bash
    git clone https://github.com/your-username/portfolio-website.git
    ```

2. Navigate to the project directory:

    ```bash
    cd portfolio-website
    ```

3. Open the `index.html` file in your preferred code editor and customize the content to match your personal details and preferences.

4. Customize the CSS styles in the `styles.css` file to adjust colors, fonts, and other design elements.

5. To switch between themes, modify the `theme-switcher.js` file or add new theme stylesheets.

## Usage

- Open the `index.html` file in a web browser to view your portfolio.

- Customize the content in the HTML file to include your personal details, projects, and achievements.

- Explore the CSS files to modify the styling and layout of your portfolio.

## Theme Customization

The `theme-switcher.js` file allows you to switch between different themes. Customize the themes by modifying the corresponding CSS files (e.g., `light-theme.css`, `dark-theme.css`).

```javascript
function toggleTheme() {
    const themeLink = document.getElementById('theme-link');
    const currentTheme = themeLink.getAttribute('href');
    const newTheme = currentTheme.includes('light') ? 'dark-theme.css' : 'light-theme.css';

    themeLink.setAttribute('href', newTheme);
}