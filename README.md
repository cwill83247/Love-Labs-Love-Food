# Love Labs , Love Food - Milestone Project 1

## Purpose of the website.

The website was created, as I am a Labrador owner and often as a family we want to make a day of it, either at the beach or in the mountains. Can often be tricky finding places that you can eat, and also take our dog.

## User Stories

As a user I want to plan my weekend dog walk.
As a user i want to go out for a meal, but no leave my dog at home.
as a user i want to find somewhere to eat that has been reviewed by fellow dog lovers. 

## Wireframes
Miro was used to create the wireframes for desktop and mobile tablet views
https://miro.com/app/board/uXjVO3quqfI=/?share_link_id=544111054445

![Love Labs screen mockups](https://github.com/cwill83247/love-labs-love-food/blob/main/assets/images/lovelabs_mockup.PNG)

## Features

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

## Future Features/improvements

### Venues Page
Addition of a searchable venue page, including interactive map to users can narrow down by post code, area or attraction.

### Gallery
Dynamic images from social media channels that include the hastag #LLLF or #Love Labs Love Food.

# Typography 
Lobster font was used from https://fonts.google.com 
for the header and navigation bar combined with Icons from https://fontawesome.com

# Validation
HTML - Validator used - https://validator.w3.org/
Passes all test

Accessibility - Lighthouse Viewer chrome developer tools - https://developers.google.com/web/tools/lighthouse
All pages achieve 100%

CSS - Jigsaw W3C Validator CSS - https://jigsaw.w3.org/css-validator/
This document validates as CSS level 3 + SVG !
 
 # Testing ( must demonstrate testing and fixes)
 Testing was carried out using Microsoft Edge and Google Chrome
 Google chrome developer tools was used to test repsonsiveness in different screen sizes.
 
 Index Page
 Links were tested to ensure worked as expected
 external Links were tested to ensure open in a new page
 Colour and Design was tested to ensure text was readable and deisgn didnt detract form content.
 Resposniveness was tested using Google chrome developer tools

 Gallery Page
 Links were tested to ensure work as expected
 Overlay was checked to ensure images behind didnt interfer with text.
 external Links were tested to ensure open in a new page
 Colour and Design was tested to ensure text was readable and design didnt detract form content.
 Resposniveness was tested using Google chrome developer tools.

 Contact Page
 Links were tested to ensure work as expected
 external Links were tested to ensure open in a new page
 Colour and Design was tested to ensure text was readable and deisgn didnt detract form content.
 Resposniveness was tested using Google chrome developer tools.
 Form fields were tested to ensure required fields worked as expected.

## Bugs and Fixes
When using Fixed haader/navigation - text is lying underneath
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

# Deployed Site
The site was deployed to GitHib pages using Gitpod - git push command.
https://cwill83247.github.io/love-labs-love-food/

# Technology used

HTML - to build the strucutre of the site
Bootstrap 5 - CSS and layout
CSS - to style content
Javascript - to create the collapisble menu when on smaller screen sizes.
Gitpod - was the IDe used to code the site.
GitHub - was the repository used for source control, and publishignthe live site.

# Credits

Bootstrap 5 - used <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

Hero Image - thank you to Yogiraj Banerji for the image https://unsplash.com/photos/HyIRIzPKG9A?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink
unsplash.com

Background image - thank you to Lily Banse https://unsplash.com/photos/-YHSwy6uqvk?utm_source=unsplash&utm_medium=referral&utm_content=creditShareLink

Fonts - https://fonts.google.com/
Header Lobster Font -  https://fonts.googleapis.com/css2?family=Lobster&display=swap'

Icons - https://fontawesome.com
https://fontawesome.com/icons/face-grin-hearts?s=solid
https://fontawesome.com/icons/paw?s=solid
## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you so do not share it. If you accidentally make it public then you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!
