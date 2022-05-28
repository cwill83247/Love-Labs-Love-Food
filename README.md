# Love Labs , Love Food - Milestone Project 1

## Purpose of the website.

The website was created, as I am a Labrador owner and often as a family we want to make a day of it, either at the beach or in the mountains. Can often be tricky finding places that you can eat, and also take our dog.

- Link to Live site https://cwill83247.github.io/love-labs-love-food/

## User stories

- As a user I want to plan my weekend dog walk.
- As a user i want to go out for a meal, but no leave my dog at home.
- as a user i want to find somewhere to eat that has been reviewed by fellow dog lovers. 

## Wireframes
Miro was used to create the wireframes for desktop and mobile tablet views
https://miro.com/app/board/uXjVO3quqfI=/?share_link_id=544111054445

![Love Labs screen mockups](https://github.com/cwill83247/love-labs-love-food/blob/main/assets/images/lovelabs_mockup.PNG)

# Features

### Header
The header and navigation is simple, clean and consistent throughout the site. Helping the user easily navigate the site.

### Footer
The footer is consisten thtroughout the site, and contains link to the main social media channels

### Home Page
The home page has been designed to clean, and contain information abotu the site that will allow a user to quickly understand the purpose of the site.

On the home page shows a snapshot of this months featured places to eat.

### Gallery
The gallery page is to showcase owners, food and there Labradors.

### Contact Page
The contact page is for users ot prpvide general comments, or for owners of food establishements to contact us to be added to our list of venues.

# Future Features/improvements

### Venues Page
Addition of a searchable venue page, including interactive map to users can narrow down by post code, area or attraction.

### Gallery
Dynamic images from social media channels that include the hastag #LLLF or #Love Labs Love Food.

## Typography 
Lobster font was used from https://fonts.google.com 
for the header and navigation bar combined with Icons from https://fontawesome.com

 # Testing and Validation
 
 Testing was carried out using Microsoft Edge and Google Chrome
 Google chrome developer tools was used to test repsonsiveness in different screen sizes.
 
 Index Page
 Links were tested to ensure worked as expected
 external Links were tested to ensure open in a new page
 Colour and Design was tested to ensure text was readable and deisgn didnt detract form content.
 Responsiveness was tested using Google chrome developer tools

 Gallery Page
 Links were tested to ensure work as expected
 Overlay was checked to ensure images behind didnt interfer with text.
 external Links were tested to ensure open in a new page
 Colour and Design was tested to ensure text was readable and design didnt detract form content.
 Responsiveness was tested using Google chrome developer tools.

 Contact Page
 Links were tested to ensure work as expected
 external Links were tested to ensure open in a new page
 Colour and Design was tested to ensure text was readable and deisgn didnt detract form content.
 Responsiveness was tested using Google chrome developer tools.
 Form fields were tested to ensure required fields worked as expected.

Validation

- HTML - Validator used - https://validator.w3.org/
Passes all test

- Accessibility - Lighthouse Viewer chrome developer tools - https://developers.google.com/web/tools/lighthouse
All pages achieve 100%

- CSS - Jigsaw W3C Validator CSS - https://jigsaw.w3.org/css-validator/
This document validates as CSS level 3 + SVG !

## Bugs and Fixes
When using Fixed header/navigation - text is lying underneath
removed -- <nav class="navbar navbar-expand-md navbar-dark fixed-top bg-dark">
replaced with -- <nav class="navbar navbar-expand-md navbar-dark bg-dark">

Navigation - within the header navigation would sit to the right of my page
Fix: Added Flex in CSS to postion.

Layout on Widescreen monitors - Site stretched across all screen sizes which coudl result in distorted site
Fix: Applied a container Div to wrap content.

Mobile device and Hero Image - hero image was overlaying header when on amobile screen size
Fix: used media query and addign additonal padding to prevent the overlay

W3C Validation
Index.html page - The element a must not appear as a descendant of the button element.
Failed code:<button type="button" class="btn btn-primary btn-lg px-4 me-md-2"><a href="#dog-friendly-venues">Lets eat</a></button>
Fixed code: <a href="#dog-friendly-venues" class="btn btn-primary btn-lg px-4 me-md-2">Lets eat</a>

Attribute a not allowed on element a at this point.
Failed code: <a href="https://www.facebook.com/TheWatermillOgmore/" a target="_blank">
Fixed code: <a href="https://www.facebook.com/TheWatermillOgmore/" target="_blank">

Quote " in attribute name. Probable cause: Matching quote missing somewhere earlier.
Failed code:<class="mb-3 me-2 mb-md-0 text-muted text-decoration-none lh-1">
Fixed code: removed as unecessary

# Technology used

HTML - to build the strucutre of the site
Bootstrap 5 - CSS and layout
CSS - to style content
Javascript - to create the collapisble menu when on smaller screen sizes.
Gitpod - was the IDe used to code the site.
GitHub - was the repository used for source control, and publishign the live site.
Google Fonts - used for the Logo font
FontAwesome - used for icons
PhotosShop CS - used to adjust theimage sizes
Unsplash.com - used for images.

# Deployment

## GitPod
The chrome browser plugin was used for gitpod, this adds a link via your githb repository so you can access the Gitpod IDE

### Commands and keyboard shortcuts used:
- ctrl + s was used to save the any ammendments to the page
- python3 -m http.server - was used to view and test site before pushing live.
- git add  was used to add pages to the stage area
- git commit -m "fix: message here" was used to comit them them to github  and provide a relevant message to the changes that had been made.
- git push was used to push the changes upto Github for public viewing. 

## Github
To deploy a web page in github pages 
- Click on settings.
- scroll down to Pages (LEFT HAND SIDE MENU)
- Click the drop down menu 
- Select your branch for your project 
- Click Save.

You will then receive a notificationwith the link to your deployed site. 

**Note**  It can take a few minutes for your live site to be available 

Live site
https://cwill83247.github.io/love-labs-love-food/

# Credits

Bootstrap 5 <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

Hero Image - thank you to Yogiraj Banerji for the image https://unsplash.com/photos/HyIRIzPKG9A?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
unsplash.com

Background image - thank you to Lily Banse https://unsplash.com/photos/-YHSwy6uqvk?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink

Fonts - https://fonts.google.com/
Header Lobster Font -  https://fonts.googleapis.com/css2?family=Lobster&display=swap'

Icons - https://fontawesome.com
https://fontawesome.com/icons/face-grin-hearts?s=solid
https://fontawesome.com/icons/paw?s=solid

codeinstitute.com - CSS styling for hero image used and tweaked as part of design. 

Gallery Images - https://unsplash.com

- Lucrezia Carnelos  - https://unsplash.com/photos/0liYTl4dJxk?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink 
- Noémi Macavei-Katócz  - https://unsplash.com/photos/0liYTl4dJxk?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Joe Hughes - https://unsplash.com/photos/T0EddJ3PiXo?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Ben Hanson - https://unsplash.com/photos/9jwBuJFdooc?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Lily Banse - https://unsplash.com/photos/-YHSwy6uqvk?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Yogiraj Banerji - https://unsplash.com/photos/HyIRIzPKG9A?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Daniel Brunsteiner  - https://unsplash.com/photos/_jd5ryWK5J4?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Nima Naseri  - https://unsplash.com/photos/XDA0KHDPBsc?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Chad Montano - https://unsplash.com/photos/eeqbbemH9-c?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Anna Tukhfatullina Food Photographer/Stylist - https://unsplash.com/photos/eeqbbemH9-c?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
- Eaters Collective - https://unsplash.com/photos/pLKgCsBOiw4?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink

Favicon - https://favicon.io/emoji-favicons/beating-heart