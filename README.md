
# Ubuntu Outdoor Adventures

A responsive, multi-page adventure tourism website developed using HTML5 and CSS3. The project demonstrates front-end web development principles, accessible design, responsive layouts, and structured website navigation.

## Project Overview

Ubuntu Outdoor Adventures is a fictional South African tourism company offering outdoor activities such as hiking, camping, mountain biking, and guided nature experiences.

The website was developed as part of my **Designing and Developing a Website (DDEW102)** Formative Assessment 1 at the Academic Institute of Excellence (AIE).

The project focuses on creating a website that is accessible, user-friendly, visually consistent, and adaptable to different screen sizes.

## Technologies Used

- HTML5
- CSS3
- CSS Flexbox
- CSS Grid
- CSS Media Queries
- HTML5 Form Controls
- Visual Studio Code
- W3C HTML and CSS Validation Tools
- diagrams.net (draw.io)
- Android Emulator for mobile layout testing

## Website Features

### 1. Multi-Page Website
- Home page introducing the company and its activities
- About Us page
- Tour Packages page
- Contact Us page with a booking enquiry form
- Relative navigation links between pages
- Internal navigation using named fragments

### 2. Responsive Web Design
- Layouts that adapt to desktop and mobile screen sizes
- CSS media queries for smaller displays
- Flexbox layouts for activity cards and tour packages
- CSS Grid for adventure package highlights
- HTML5 picture elements for responsive images

### 3. CSS Styling
- External stylesheets
- Consistent typography and colour schemes
- Rounded corners, borders, and box shadows
- Text shadows and gradient backgrounds
- RGBA and HSLA colours
- CSS sprites for activity icons
- Separate print stylesheet

### 4. Tour Packages
- Adventure package information
- A structured HTML table displaying five packages
- Table headers, body, and footer
- Alternating table row styling
- Responsive package cards

### 5. Booking Enquiry Form
- Personal information fields
- Preferred adventure package selection
- Number of participants
- Preferred booking date and time
- Favourite activity selection
- Additional comments
- HTML5 input validation features
- Fieldsets and legends for logical grouping
- Keyboard accessibility attributes

**Note:** The booking form is a front-end demonstration. It does not currently include a back-end service for processing or storing enquiries.

## Project Structure

```text
Ubuntu-Outdoor-Adventures/
│
├── index.html
├── styles.css
├── printing.css
│
├── pages/
│   ├── about.html
│   ├── packages.html
│   └── contact.html
│
└── images/
    ├── activity-sprite.png
    ├── biking-128.png
    ├── biking-icon.png
    ├── camping-128.png
    ├── camping-icon.png
    ├── hiking-128.png
    └── hiking-icon.png
```

## Running the Project

1. Download or clone the repository.
2. Open the project folder in Visual Studio Code.
3. Open `index.html` in a web browser.
4. Navigate between the website pages using the navigation menu.

No installation or additional dependencies are required for the static website.

## Assessment Background

**Institution:** Academic Institute of Excellence (AIE)  
**Module:** Designing and Developing a Website (DDEW102)  
**Assessment:** Formative Assessment 1  
**Year:** 2026  
**Result:** 107/120 (89.2%)

The assessment covered five main areas:

1. Internet, World Wide Web, and HTML5 fundamentals
2. CSS, visual elements, and graphics
3. Web design and page layouts
4. Hyperlinks, responsive layouts, and tables
5. HTML5 forms and accessibility

## Known Issues and Planned Improvements

The original assessment submission has been retained to demonstrate the work completed at the time of submission.

The following areas have been identified for future improvement:

- Restore missing image assets referenced by the HTML.
- Improve the visual appearance and overall presentation.
- Review responsive layouts across additional screen sizes.
- Improve keyboard navigation and accessibility.
- Refine form validation and usability.
- Implement functional server-side booking enquiry processing.
- Expand testing and documentation.

Improvements will be documented separately to demonstrate continued learning and development.

## What I Learned

Through this project, I gained practical experience in:

- Structuring multi-page websites using semantic HTML5.
- Applying CSS styling consistently across multiple pages.
- Designing responsive layouts using Flexbox, Grid, and media queries.
- Organising website files and managing relative paths.
- Creating and styling HTML tables and forms.
- Testing layouts on desktop and mobile devices.
- Validating HTML and CSS.
- Identifying and resolving layout issues.

One of the challenges I encountered involved floated elements affecting the position of the footer. I investigated the issue and applied a CSS clearfix to correct the layout.

This experience strengthened my understanding of how CSS layout techniques affect surrounding elements.

## Future Development

This repository serves as both an academic project and a record of my front-end development progress.

Future updates may include improved styling, enhanced accessibility, and functional booking enquiry processing.

## Author

**Charlean du Plessis**

Software Engineering Student  
Academic Institute of Excellence (AIE)

*This project was developed for educational and portfolio purposes. Ubuntu Outdoor Adventures is a fictional company used in the assessment scenario.*
