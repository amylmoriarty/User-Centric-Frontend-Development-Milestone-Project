

# NI Ballet School
Stream One Project: User Centric Frontend Development - Code Institute 

This is my website for a ballet school. 

The website tells the user about the school, how to get in contact via a contact form and details in the footer, 
allows the user to view upcoming class schedules and register for the classes.

 
## UX

My goal was to make information accessible on the site, while striving for a user friendly but appealing design.
That is why I adopted a mobile first approach and scaled up from there.

I specifically chose to use Glidden Pink Ballet Slipper / #f4e3d4 as the main background colour as I felt it suited the theme of the brief.
I paired this with the red and blue accent colours as I felt they compliment the dusky pink.

During this project, following advice from my mentor Jonathan regarding accessibility I changed my measurements from pixels to rem. 
This will accommomodate more users of the website and makes the overall design more accessible. 

I made the decision to add a contact page and have the contact details in the footer for ease of access. 
The aim of that is to encourage somebody to pick up the phone for a quick enquiry while also allowing them to send an email for a more detailed message or get in contact after opening hours.

As a potential student I want information on classes for my age group.

As a parent of a potential student I want information about the teachers credentials and relevant vetting.

As an examiner I want to be able to contact the school with their students exam results.

As a staff member from the school I want to increase engagement and following on our social media profiles.


The wireframes for each page are available in the wireframe directory here https://github.com/amylmoriarty/User-Centric-Frontend-Development-Milestone-Project/tree/master/wireframes


## Features

### Existing Features

Home page - index.html The main focus of the home page is the banner to advertise the classes on instagram. 
I have used a bootstrap jumbotron with a background image and a link to the account which opens on a seperate page to allow users to continue browsing the website after following on Instagram.

About.html - I wanted to showcase the teachers experience here, I have also included the relevant dance qualification logos in the footer as this school is based in Northern Ireland and works with students of all backgrounds, 
I wanted this to be immediately obvious to the users.

Contact.html Users can get in touch with the school via the contact form or in the footer.

Schedule.html Users can register for upcoming classes via email, browse the timetables for the classes and are reminded they can participate in the live classes on social media.


### Features Left to Implement

In the future, I would wire up the contact forms to be able to send an email to the school. 

I would also link to different sections of the site via the banners.

## Technologies Used

1. HTML
2. CSS
3. Bootstrap [https://getbootstrap.com/]

## Testing

This site was continiously tested manually with each new piece of functionality in browser dev tools for compatibility and responsiveness.

I tested each of the navbar links to ensure they direct you to the correct page.
I tested each of the social media links in the footer to ensure they direct you to the correct site while also opening in a new tab.
I tested the links in the footer for the contact details to ensure they direct you to your email or phone client.
I tested each input in the contact form to ensure they werent submitting unless filled in correctly.
I tested each of the inputs in the registration form paying particular attention to the phone number input, this will only allow you to submit with an 11 digit number  inputted.
I tested the navbar in dev tools on multiple browsers to ensure it displayed correctly and was fully responsive.

I validated my HTML with https://validator.w3.org/ for each page and recieved no errors.
I validated my css with https://jigsaw.w3.org/css-validator/validator and recieved no errors.

## Bugs

During testing I noticed what appears to be a bug, the custom styling for the jumbotron had to be at the bottom of the hierarchy in order to be applied to all the banner elements. 
This is why I have inserted it at the bottom of the stylesheet with a comment to identify it.

## Deployment

The live site is deployed on GitHub pages. It uses the master branch. It updates each time there is a new push to the repository.
https://amylmoriarty.github.io/User-Centric-Frontend-Development-Milestone-Project/index.html


## Credits

### Content
All content was written by me.

### Media

Banner images were obtained from stock image libraries.

Home page banner  https://www.pexels.com/photo/adorable-little-girl-in-ballet-dress-sitting-on-table-3887537/

Contact page banner https://images.unsplash.com/photo-1525598912003-663126343e1f?ixlib=rb-1.2.1&

Schedule page banner  https://www.pexels.com/photo/black-framed-wayfarer-style-eyeglasses-on-white-surface-917293/ 

Favicon image was obtained from https://pixabay.com/vectors/ballet-shoes-black-dance-ballerina-311217/ and resized to suit purpose.
### Acknowledgements

The jumbotron uses a background image which leans on the hero image tutorial here: https://www.w3schools.com/howto/howto_css_hero_image.asp it was significantly edited to suit the style and layout of the site.

A special thanks to my mentor Jonathan for his excellent guidance and support throughout this project. 