
# Assessment Feedback and Improvement Report

## Ubuntu Outdoor Adventures

**Developer:** Charlean du Plessis  
**Institution:** Academic Institute of Excellence (AIE)  
**Module:** Designing and Developing a Website (DDEW102)  
**Assessment:** Formative Assessment 1  
**Year:** 2026  
**Result:** 107/120 (89.2%)

---

## 1. Purpose of This Report

I developed the Ubuntu Outdoor Adventures website as part of my DDEW102 Formative Assessment 1.

The purpose of this report is to reflect on my assessment feedback, identify areas where my work could be improved, and explain how I would approach those improvements.

I have retained my original assessment code in this repository to demonstrate the work I completed at the time of submission.

This report represents my reflection and proposed improvements rather than a claim that all corrections have already been implemented.

## 2. Assessment Results

| Question | Topic | Marks |
|---|---|---|
| Question 1 | Internet, Web and HTML5 Fundamentals | 22/25 |
| Question 2 | CSS, Visual Elements and Graphics | 23/25 |
| Question 3 | Web Design and Page Layout | 20/25 |
| Question 4 | Hyperlinks, Layouts and Tables | 24/25 |
| Question 5 | HTML5 Forms and Accessibility | 18/20 |
| **Total** | | **107/120 (89.2%)** |

The marking report identified several strengths in my practical development work, particularly my implementation of CSS, responsive layouts, HTML tables, navigation and form controls.

The main areas identified for improvement were missing image resources, the depth of some written explanations, and aspects of the website's visual design and layout.

## 3. Question 1: HTML5 Fundamentals

**Mark: 22/25**

### What I Implemented

I demonstrated my understanding of the Internet, World Wide Web, HTML5 and web standards.

I also created the initial homepage using semantic HTML5 elements, navigation links and the required website content.

### Feedback Received

The marking report indicated that my explanation of the evolution of the Internet and the Web was too brief.

It also identified limited detail in my comparison of HTML, XHTML and HTML5, and described the initial homepage as relatively basic.

### How I Would Improve

I would expand my technical explanations by including important historical developments such as ARPANET, TCP/IP and the creation of the World Wide Web.

I would provide more detailed comparisons of markup languages and use practical examples to demonstrate their differences.

For the website itself, I would improve the homepage's visual hierarchy, spacing and presentation while maintaining semantic HTML5 structure.

### What I Learned

I learned that demonstrating technical knowledge requires more than identifying the correct concepts. Clear explanations and relevant examples help demonstrate a deeper understanding of the technologies being used.

## 4. Question 2: CSS and Visual Elements

**Mark: 23/25**

### What I Implemented

I created and linked an external CSS stylesheet.

I implemented element, class, ID and descendant selectors, along with borders, rounded corners, shadows, opacity, gradients and CSS colour functions.

I also used the HTML5 figure and figcaption elements.

### Feedback Received

The marking report confirmed that the required CSS properties were implemented successfully.

However, the outdoor activity image referenced in the HTML was not included in the submitted project files.

As a result, the image could not display correctly.

### How I Would Improve

I would review the image references in the HTML and compare them against the files stored in the project.

I would restore the missing image resources and verify that their paths work correctly.

I would also review image dimensions, alternative text and responsive styling.

Before preparing another submission, I would test the website using a clean copy of the project folder rather than relying only on files already available on my development computer.

### What I Learned

I learned that correct HTML and CSS code does not guarantee that a complete website will work after being transferred to another computer.

All required assets must be included, and relative file paths must be tested.

## 5. Question 3: Web Design and Responsive Layouts

**Mark: 20/25**

### What I Implemented

I identified the target audience, developed a sitemap, and created a homepage wireframe.

I implemented universal design principles, CSS box model properties, a two-column float layout, Flexbox and responsive images using the picture element.

I also tested the layout at different screen sizes.

### Feedback Received

The marking report indicated that my discussion of visual design principles was fairly general.

It also identified limited use of CSS positioning and missing responsive image files.

The sitemap included a Booking Enquiry page that was not created as a separate webpage.

### How I Would Improve

I would expand the design documentation to explain how contrast, alignment, spacing, grouping and hierarchy influenced specific layout decisions.

I would review the sitemap and ensure that it accurately represents the implemented website structure.

I would also consider replacing float-based page layouts with CSS Grid or Flexbox where appropriate, while retaining the original implementation as evidence of my understanding of floats.

I would restore the missing responsive image resources and test how the picture element selects images at different viewport widths.

### A Layout Problem I Solved

During development, I encountered a problem where the footer moved into the floated content area.

I investigated the relationship between floated elements and their parent container.

I corrected the problem by applying a CSS clearfix, which allowed the main content area to contain the floated columns correctly.

This was an important learning experience because it required me to identify the cause of a layout problem rather than simply adjusting the appearance of the footer.

### What I Learned

I developed a better understanding of CSS layout behaviour, responsive design and the importance of testing changes across different screen sizes.

I also learned that design planning documents should remain consistent with the final implementation.

## 6. Question 4: Website Navigation, Layouts and Tables

**Mark: 24/25**

### What I Implemented

I expanded the website to include:

- About Us
- Tour Packages
- Contact Us

I implemented relative hyperlinks, named fragments, CSS sprites, a print stylesheet, media queries, a five-package HTML table, Flexbox and CSS Grid.

### Feedback Received

The marking report confirmed that the required technical features were implemented successfully.

The main improvement identified was that some explanations of how these techniques benefit users were too brief.

### How I Would Improve

I would provide more detailed explanations of how each technique contributes to website usability.

For example, I would explain how print stylesheets improve printed output, how media queries support smaller displays, and how CSS sprites allow multiple icons to be displayed using a single image resource.

I would also test the consistency of navigation and page styling throughout the website.

### What I Learned

This section strengthened my understanding of how multiple HTML and CSS techniques can work together in a structured, multi-page website.

## 7. Question 5: Forms and Accessibility

**Mark: 18/20**

### What I Implemented

I created an online booking enquiry form on the Contact Us page.

The form includes personal information fields, package selection, booking details and additional comments.

I implemented HTML5 form controls, labels, fieldsets, legends, accesskey attributes and tabindex attributes.

### Feedback Received

The marking report confirmed that the required form controls were implemented.

The main areas for improvement were the explanations of server-side processing, CGI and the usability benefits of the accessibility features.

### How I Would Improve

I would expand my explanations of how HTML forms communicate with server-side applications and how submitted information is validated, processed and stored.

I would also review the form's keyboard navigation and accessibility.

As a future development exercise, I would connect the booking enquiry form to a back-end application.

This could include server-side validation, confirmation messages and secure storage of enquiries.

The original assessment form is a front-end demonstration and does not currently provide a complete booking-processing service.

### What I Learned

I learned that developing a form involves more than adding input fields.

A professional form should also consider accessibility, validation, user feedback and how information is processed after submission.

## 8. Overall Technical Improvements

Based on the assessment feedback and my own review, I have identified the following improvements.

### Priority 1: Correct Missing Resources

- [ ] Restore the missing outdoor activity images.
- [ ] Check all image references.
- [ ] Verify relative file paths.
- [ ] Test the website from a clean project copy.

### Priority 2: Improve Accessibility

- [ ] Review alternative text for images.
- [ ] Test keyboard navigation.
- [ ] Review form labels and focus order.
- [ ] Check colour contrast.
- [ ] Review form usability on mobile devices.

### Priority 3: Improve Responsive Design

- [ ] Test additional viewport sizes.
- [ ] Review the two-column layout.
- [ ] Improve responsive image handling.
- [ ] Check tables and forms on smaller screens.
- [ ] Review opportunities to use modern CSS layout techniques.

### Priority 4: Improve Documentation

- [ ] Expand technical explanations.
- [ ] Update the sitemap to match the implemented website.
- [ ] Document testing results.
- [ ] Record future improvements and corrections.

### Priority 5: Future Functionality

- [ ] Implement back-end booking enquiry processing.
- [ ] Add server-side form validation.
- [ ] Provide submission confirmation messages.
- [ ] Consider secure storage of booking enquiries.

## 9. Reflection on My Development Progress

This project helped me move from understanding individual HTML and CSS concepts to applying them in a complete multi-page website.

I gained practical experience with semantic HTML, CSS styling, responsive layouts, navigation, tables, forms and validation.

I also encountered problems that required troubleshooting, particularly with CSS floats and missing resources.

Although the assessment achieved 89.2%, I recognise that there are areas where the website and my technical explanations could be improved.

I see the feedback as an opportunity to strengthen my development skills and demonstrate that I can evaluate my work critically.

## 10. Conclusion

Ubuntu Outdoor Adventures represents an important stage in my front-end web development studies.

The original project demonstrates the technical requirements I implemented during the assessment.

This report documents the feedback I received, the problems identified and the improvements I would make in future development.

My goal is to continue improving the project while maintaining an accurate record of my original work and development progress.

---

**Author:** Charlean du Plessis  
**Project:** Ubuntu Outdoor Adventures  
**Assessment:** DDEW102 Formative Assessment 1  
**Year:** 2026

*This document is a personal development reflection based on the assessment marking report and original submission. It is not an official amended assessment result.*
