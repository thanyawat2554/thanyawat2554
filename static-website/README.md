# Static Website Documentation

## Overview
This project is a simple static website that consists of HTML, CSS, and JavaScript files. It is designed to be deployed on GitHub Pages.

## Project Structure
```
static-website
├── src
│   ├── index.html        # Main HTML document
│   ├── styles
│   │   └── style.css     # CSS styles for the website
│   └── scripts
│       └── app.js       # JavaScript code for interactivity
├── .github
│   └── workflows
│       └── static.yml    # GitHub Actions workflow for deployment
└── README.md             # Project documentation
```

## Getting Started

### Prerequisites
- A GitHub account
- Basic knowledge of HTML, CSS, and JavaScript

### Setup
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/yourusername/static-website.git
   ```
2. Navigate to the project directory:
   ```
   cd static-website
   ```

### Running the Website Locally
To view the website locally, open the `src/index.html` file in your web browser.

### Deployment
This project uses GitHub Actions to deploy the static website to GitHub Pages. To deploy:
1. Push your changes to the `main` branch of the repository.
2. The GitHub Actions workflow defined in `.github/workflows/static.yml` will automatically run and deploy the website.

### Customization
- Modify `src/styles/style.css` to change the appearance of the website.
- Update `src/scripts/app.js` to add interactivity.
- Edit `src/index.html` to change the content and structure of the webpage.

## License
This project is licensed under the MIT License.