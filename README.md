# ID-Assignment-1
# Personal Portfolio Site
This website is to give the site's target audience which are recruiters, a better understanding about myself. It is to tell the recruiters a brief description about myself about what I do and what I have done such as my education, programming languages and software I know. The recruiters will also be able to see the past works/projects I have done before to get a better understanding about my experience.

## Design Process
 
The website is for recruiters to consider reaching out and hiring me after looking at my portfolio. This design achieves that by spliting the website into 3 parts, "About", "Projects", "Contact". The About Page will let the user first look at a brief introduction about myself, and move on to see my education/where I have studied at, and lastly my skills. This layout will let the recruiters see my competency to see if they my experience is beneficial to them hiring me. After the "About" page the users can use the navigation tool to go to the projects so that the recruiters can see if my works reach the standards they would want to consider hiring me. After that they can navigate to the contact page to reach out to me by sending a message there and also by the links(email and LinkedIn) provided in that page.
This is the [XD share url](https://xd.adobe.com/view/fdc00e94-1109-4d14-8f50-8c8b9b7ca216-a893/). The wireframe for this is located in the ID-Assignment-1 folder.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user, I want to be able to toggle between different pages , so that I can view the contents of each page. (Hence, I added the navigation function)
- As a recruiter, I want to be able to reach out to the website owner to ask more questions or to recruit them. (Hence, I added the contact page for the recruiters to be able to send a message through the forms or reach out to me through email or LinkedIn.)
- As a recruiter, I want to learn more about the educational background and experience of the website owner so that I can consider hiring them. (Hence, I added the about page for the recruiter to have a better understanding of my background)
- As a recruiter, I want to see the past works/projects they have done to evaluate if I would want to hire them.(Hence, I added the projects page for recruiter to determine my value after looking at my works)

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- About Page - allows recruiters to view a short introduction about myself, where I have studied and my skills()
- Project Page - allows recruiters to view the works I have done. When the user hovers over and image, a drop shadow is applied on that image.
- Contact Page - allows recruiters to send a message after inputing their name and email(writing a message is optional). After submitting the message, an alert will pop up to notify the user that the input has been submitted successfully and thanks the user for their input. There are 2 links below the message section which redirects users to another tab if they would wish to email me or visit my LinkedIn profile.
- Navigation Menu - allows users to toggle between the 3 different pages. The navigation header will change based on the screen size, to better accomodate to the screen sizes of the user's devices.

### Features Left to Implement
- Add animations for images in the project page to slide in as the user scrolls down
- A page which shows my certifications
- For the project page, I could implement a feature that shows the description of each project when the user hovers over the image.

## Technologies Used

In this section, you should mention all of the languages, frameworks, libraries, and any other tools that you have used to construct this project. For each, provide its name, a link to its official site and a short sentence of why it was used.
- [HTML](https://html.com/)
    - used HTML to input the content of the website
- [CSS]
    - used CSS to style the website
- [JavaScript]
    - used JavaScript to add an alert message after submitting a form


## Testing

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact" page
    2. Try to submit the empty form and verify that an error message about the required fields(Name, Email) appears
    3. Try to submit the form without '@' in the email and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that an alert with a success message appears.

2. External Links:
    1. Go to the "Contact" page
    2. Click on the link and verify that the link opens in a separate tab.

3. Navigation Tab:
    1. Go to mobile view/less than 888px and verify that the navigation bar changes to a menu icon that opens the navigation page after clicking on it.
    2. Try to scroll down and up when the navigation page is opened and verify that both the navigation header and page is in a fixed position and does not show empty gaps or empty navigation page
    3. Try to visit other pages using the navigation tab and verify that you are able to toggle between each page with no issues.

4. About Page:
    1. Go to desktop view and make sure that each section is displayed in a horizontal format, the about me section should show the write up on the left and picture on the right. Education section shows schools in ascending order, from primary to teritary from left to right. Skills section shows the languages on the left, and softwares on the right.
    2. Go to mobile view and ensure that each section is displayed in a vertical format, about me section shows a picture on top of the write up. Education section shows primary to teritary, top to bottom. Skills section shows languages above the softwares.

5. Projects Page:
    1. Go to desktop view and ensure that the images are displayed in 2 columns with the same width.
    2. Go to mobile view and ensure that the images are now displayed in a single column with the same width.
    3. Hover over an image and verify that there is a drop shadow for that image.


You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

-After completing the navigation header, when I opened the menu in mobile view and scrolled down, I discovered that the position of the header was not fixed so there was a gap in the navigation menu in mobile view. I fixed it by setting the position of the navigation header to fixed.


## Credits

### Content
- The text for education was copied from my FP 1 Assignment in semester 1 where we had to create a personal branding website. [Personal Branding Website](https://s10222211.wixsite.com/my-site)

### Media
- The photos used in this site were provided by myself

### Acknowledgements
- I received inspiration of the layout of the contact page from [JeanBeanSprout](https://jeanbeansprout.bigcartel.com/contact)
