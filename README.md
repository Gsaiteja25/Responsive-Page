# Responsive Website Using CSS Media Queries

## Task 4 - Web Development Internship

### Objective

Convert a desktop-only webpage into a mobile-friendly responsive website using CSS Media Queries.

### Tools Used

* HTML5
* CSS3
* Visual Studio Code
* Chrome DevTools

### Features

* Responsive navigation menu
* Flexible card layout using Flexbox
* Mobile-friendly design
* Responsive images
* Media Queries for screens smaller than 768px
* No horizontal scrolling on mobile devices

### Project Structure

Responsive-Website/

├── index.html

├── style.css

└── README.md

### How to Run the Project

1. Download or clone the repository.
2. Open the project folder in VS Code.
3. Open `index.html` using Live Server.
4. View the website in your browser.

### Testing Responsive Design

1. Open Chrome Browser.
2. Press `F12` to open Developer Tools.
3. Click the Device Toolbar icon.
4. Select a mobile device such as:

   * iPhone SE
   * iPhone 14 Pro
   * Samsung Galaxy S20
   * iPad

### Media Query Used

```css
@media screen and (max-width:768px){

    .nav-menu{
        flex-direction:column;
        align-items:center;
    }

    .container{
        flex-direction:column;
    }

    .card{
        width:100%;
    }

    h1{
        font-size:24px;
    }

    h2{
        font-size:20px;
    }

    p{
        font-size:14px;
    }
}
```

### Learning Outcomes

* Understanding CSS Media Queries
* Creating Mobile-Friendly Layouts
* Responsive Navigation Design
* Responsive Images and Content
* Testing Websites Using Chrome DevTools

### Author

Name: Sai Teja

Internship: Web Development Internship

Task: Task 4 – Make a Website Mobile-Friendly Using CSS Media Queries
