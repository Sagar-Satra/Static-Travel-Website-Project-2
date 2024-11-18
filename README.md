# Travel Goo Website
This project is a simple static website for a travel agency named "Travel Goo." I have implemented this project in HTML and SASS preprocessor scripting language.
It showcases various sections like services, popular destinations, best packages, customer reviews, and provides a subscription form for users to stay updated with the latest news and offers.

## Table of Contents
- [Features](#features)
- [HTML Structure](#html-structure)
- [Sections](#sections)
- [CSS Styling](#CSS-Styles-Documentation)

## Features
- **Header and Navigation:** Includes links to different sections of the website with icons.
- **Main Content:**
  - **Hero Section:** Displays a promotional message with an image.
  - **About Us:** Describes the services offered by Travel Goo.
  - **Popular Destinations:** Highlights popular travel destinations.
  - **Best Packages:** Lists various travel packages with details and pricing.
  - **Booking Steps:** Explains the steps to book a trip.
  - **Customer Reviews:** Displays testimonials from customers.
  - **Subscription Form:** Allows users to subscribe for updates.

## HTML Structure
The HTML file is structured into the following main parts:
-  <header> : Contains the title.
-  <nav> : Contains the navigation menu.
-  <main> : Includes all the primary content sections.
-  <footer> : Contains contact information, quick links, and social media links.

## Sections
1. **Header and Navigation**
   - Title: Travel Goo
   - Navigation links with icons: Home, About Us, Popular Destinations, Best Packages, Customer Reviews, and Login.

2. **Hero Section**
   - Promotional heading and image with an action button.

3. **About Us**
   - Details about services such as Ticket Booking, Hotel Booking, and Tour Plans.
   - Highlighted statistics about the company.

4. **Popular Destinations**
   - Showcases top travel spots in Europe, India, and Australia.

5. **Best Packages**
   - Lists travel packages with images, duration, and pricing.

6. **Booking Steps**
   - Describes the steps to book a trip easily.

7. **Customer Reviews**
   - Displays customer testimonials with images.

8. **Subscription Form**
   - Form for users to subscribe to newsletters with full name and email validations.

9.  **Footer** 
   - Contains company information, quick links, contact details, and social media links.

## License
This project is licensed under the TravelCoo

## SCSS Styles used:
## Features

1. Variables
Store values (such as colors, fonts, or any CSS value) in variables, making your CSS more reusable and easier to maintain.

2. Nesting
Nest your CSS selectors in a way that follows the same visual hierarchy of your HTML, making the code more readable and maintaining a clear structure.

3. Partials and Import
Break your CSS into smaller, modular pieces using partials and then import them into a main stylesheet to keep your project organized.

4. Mixins
Create reusable chunks of CSS that can be included in other selectors. Mixins can also accept arguments to make them more flexible.

5. Inheritance (Extends)
Share a set of CSS properties from one selector to another, promoting code reusability and reducing redundancy.

6. Operators
Perform mathematical operations such as addition, subtraction, multiplication, and division, allowing dynamic calculation of property values.

7. Control Directives
Use logic and loops in your stylesheets, making them more dynamic with directives like `@each` for generating color classes.


## CSS Styles Documentation
Properties used:
1. box-sizing : it Defines how the total width and height of an element is calculated.
2. font-family : it Specifies the font family for text.
3. display : it Determines how an element is displayed.
4. background : it Sets the background properties for an element.
5. background-size : it Specifies the size of the background image.
6. color : it Sets the color of text.
7. background-position : itSets the starting position of a background image.
8. background-repeat : it Specifies how a background image is repeated.
9. min-height : it Sets the minimum height of an element.
10. height : it Sets the height of an element.
11. top : it Sets the top position of a positioned element.
12. padding : it Sets the padding of an element.
13. font-size : it Sets the size of the font.
14. font-weight : it Sets the boldness of the font.
15. position : it Specifies the positioning method of an element.
16. float : it Specifies whether an element should float or not.
17. width : it Sets the width of an element.
18. align-items : it Sets how flex items are aligned along the cross axis.
19. justify-content : it Sets how flex items are aligned along the main axis.
20. margin : it Sets the margin of an element.
21. text-align : it Sets the horizontal alignment of text.
22. text-decoration : it Sets the decoration of text.
23. line-height : it Sets the height of a line box.
24. border-radius : it Sets the radius of the element's corners.
25. border : it Sets the border properties of an element.
26. cursor :it  Sets the type of cursor to be displayed when pointing over an element.
27. opacity : it Sets the opacity level for an element.
28. gap :it Sets the gap between flex items.
29. box-shadow : it Adds shadow effect around an element's frame.
30. word-break : it defines how to break lines within words when necessary for fitting into the container.
31. transition : it sets the transition effects for an element when its state changes.
32. z-index : it Sets the stack order of an element.

## Global Styles
 *  Selector: it Applies universal styles to all elements, setting  box-sizing  to  border-box  and setting the default  font-family .
  body  : it Ensures the body is displayed as a block-level element.

## Header
-   header  : it Styles the header with a gradient and background image, setting the font family, color, size, and position.
-   .header  : it Uses flexbox to align and space content within the header.
-   .logo  : it Styles the logo, setting its size, weight, and position.
-   nav  : it Centers the navigation bar.
-   nav a  :  it Styles navigation links with color, text alignment, margin, and size.
-   .header-right  : it Sets the font size for elements in the header's right section.

## Main Section
-   .main-section  : Uses flexbox to center and align content, setting height and padding.
-   .main-section h2  : Sets width, height, padding, word wrap, margin, and font size for headings.
-   .main-section p  : Sets width and font size for paragraphs.
-   .main-section button  : Styles buttons with background color, border, padding, text alignment, font size, margin, cursor, and border radius.

## About Us Section
-   #aboutus  : Styles the About Us section with font settings and text alignment.
-   .aboutus-section1  : Uses flexbox to align and space content, setting height.
-   .bg-grey  : Sets the background color to grey.
-   .bookingsection  : Aligns and spaces content within the booking section.
-   .aboutus-section1-booking-format  : Styles booking format sections with height, width, padding, border radius, and flexbox layout.
-   #ticketbooking, #tourplan  : Sets the background color.
-   #hotelbooking  : Adds a shadow to the hotel booking section.
-   .aboutus-section1-booking-format figure, p  : Sets margin and padding.
-   .aboutus-section1-booking-format h5  : Styles headings with margin and padding.
-   .green, .blue, .red  : Sets text color and font size for elements.

## About Us Section 2
-   .aboutus-section2  : Positions and styles the second About Us section.
-   #worldmap  : Sets the opacity, width, and height for the world map image.
-   .aboutus-section2-subsection1  : Centers content within the second About Us subsection using absolute positioning and transforms.
-   .aboutus-section2 h3  : Styles headings with padding, word wrap, font size, and margin.
-   .aboutus-section2-subsection1 > p  : Styles paragraphs with padding, font size, and margin.

## About Us Section 3
-   .aboutus-section3  : Uses flexbox to align and space content, setting height and gap.
-   .aboutus-section3 article  : Styles articles with background color, height, width, text alignment, border radius, and flexbox layout.
-   .aboutus-section3 figure  : Sets margin and padding for figures.
-   .lightgreen  : Sets text color and font size for light green elements.
-   .aboutus-section3 figcaption  : Styles figure captions with font weight, margin, and font size.
-   .aboutus-section3 p  : Styles paragraphs with padding, margin, font size, font weight, and font family.

## Popular Section
-   #popular  : Styles the Popular section with font settings, text alignment, height, and background image.
-   .popular-container  : Removes margin.

## Best Packages
-   #best-packages  : Sets the background color and padding for the Best Packages section.
-   .btn  : Styles buttons with border, outline, padding, background color, cursor, border radius, and color.
-   .btn:hover  : Changes the background color on hover.
-   .btn.active  : Sets the active button background and text color.
-   h1  : Sets the font size and word-break property for headings.
-   .row  : Uses flexbox for layout, sets width, direction, alignment, and margin.
-   .row, .row > .column  : Adds padding between columns.
-   .row:after   Clears floats after rows.
-   .content  : Styles content with background color, border radius, box shadow, and padding.
-   .content-info  : Sets padding for content info sections.
-   .center  : Uses flexbox to center content.
-   .fw-600  : Sets font weight.
-   .flex-column  : Sets flex direction to column.
-   .clearfix  : Ensures overflow is handled.
-   .show  : Displays elements as block.
-   #filter-selection  : Uses flexbox to space filter options.
-   .package-img  : Sets width and border radius for package images.
-   .fl, .fr  : Floats elements left and right.
-   .know-more span  : Styles "know more" spans with color, text decoration, font size, and weight.
-   .location  : Styles location text with color, font size, and weight.
-   .w-210  : Sets width.
-   .flex-container  : Uses flexbox for layout.
-   .heading  : Styles headings with padding, alignment, text properties, and margin.
-   .flex-row-reverse  : Sets flex direction to row-reverse.
-   .mr-350  : Sets margin-right.
-   .mt-30  : Sets margin-top.
-   .left-img-card  : Styles image cards with background, shadow, margin, border radius, width, and height.
-   .left-img-card figure  : Sets margin, padding, width, and border radius for figures.
-   .m-10  : Sets margin.
-   .flex-grow-1, .flex-grow-2  : Sets flex-grow properties.
-   .clear  : Clears floats.

## Form Section
-   .form-section  : Uses flexbox to align and center form sections, setting margin and height.
-   .form-section > div  : Styles form containers with width, background color, border radius, padding, and flexbox layout.
-   .form-section > div > div > p  : Sets width, font weight, margin, and text alignment for paragraphs.
-   .form-section img  : Positions and styles images.
-   .form-section > div > form  : Styles forms with width, border radius, flexbox layout, and gap.
-   .form-section > div > form button  : Styles form buttons with background color, border, padding, text alignment, font size, margin, cursor, and border radius.
-   .inside-form-align  : Uses flexbox to align form elements, setting width, gap, font weight, and font size.
-   .inside-form-align input, .inside-form-align textarea  : Sets width for inputs and textareas.

## Footer
-   footer  : Styles the footer with margin, alignment, font size, and shadow.
-   .footer > p  : Sets font size for paragraphs.
-   .footersection  : Uses flexbox to align and space content within footer sections, setting gap.
-   .footersection section  : Sets width for sections.
-   .footer-logo  : Centers the footer logo.
-   .footer-logo h3  : Styles footer logo headings with font size, margin, and padding.
-   .footer-logo p  : Sets font size for footer logo paragraphs.
-   .footersection ul  : Removes list styling, padding, margin, and sets font size.
-   .footersection li  : Sets margin and padding for list items.
-   .footersection a  : Styles footer links with text decoration and color.
-   .footer-store-container  : Uses flexbox to align and space content within the store container, setting font size and gap.
-   .footer-store-subcontainer  : Uses flexbox to align and center content within store subcontainers, setting background color, width, height, border radius, and padding.
-   .store-logo  : Sets width for store logos.
-   .store-logo img  : Styles store logo images with margin and width.
-   .logo-content, .logo-content p, .logo-content span  : Sets margin, padding, and font size for logo content.

## Customer Review Section
-   .scroller  : Sets height to 100vh.
-   .scrolling-wrapper  : Uses flexbox to align and enable horizontal scrolling, hiding vertical overflow.
-   .customer-face-review  : Styles customer face reviews with position, background color, width, margin, height, and border radius.
-   .destination-review  : Sets width and border radius for destination reviews.
-   .destination-review img  : Styles destination review images with width and border radius.
-   .customer-face-review > img  : Sets width, height, and border radius for customer face review images.
-   .review-content  : Sets width for review content.
