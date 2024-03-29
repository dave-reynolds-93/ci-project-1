<h1 align="center">Maths Tuition With Dave Website</h1>

![index.html](/assets/images/indexDesktop.png)

[View the live project here.](https://dave-reynolds-93.github.io/ci-project-1/)

This is a tutoring site with the aim of attaining more students. It is aimed at parents of children studying maths, and also people studying maths. Features include information about the services, with easy navigation of multiple pages.

## User Experience (UX)

-   ### User stories

    -   #### First Time Visitor Goals

        1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the tutor.
        2. As a First Time Visitor, I want to be able to easily navigate throughout the site to find content.

    -   #### Returning Visitor Goals

        1. As a Returning Visitor, I want to find the best way to get in contact with the tutor with any questions I may have.

    -   #### Frequent User Goals
    
        1. As a Frequent User, I want to check to see if the inspirational video has changed.

-   ### Design
    -   #### Colour Scheme
        -   The two main colours used are #42f5b9, and #0f4d19. ![](/assets/images/colourContrast.png)
    -   #### Typography
        -   Lora and Source Serif 4 are the 2 fonts used throughout the website, with serif as the fallback font in case for any reason the fonts aren't being imported into the site correctly. The 2 fonts are very clean, and give the website a professional feel.
    -   #### Imagery
        -   Imagery is important. The tutor picture shows potential clients what the tutor looks like, helping them feel they know him a bit better.

*   ### Wireframes

    -   All wireframes - [View](/assets/wireframes/Wireframes.pdf)


## Features

-   Responsive on all device sizes

-   Interactive elements

## Technologies Used

### Languages Used

-   [HTML5](https://en.wikipedia.org/wiki/HTML5)
-   [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)

### Frameworks, Libraries & Programs Used

1. [Bootstrap 5.3.2:](https://getbootstrap.com/docs/4.4/getting-started/introduction/)
    - Bootstrap was used to assist with the responsiveness and styling of the website.
1. [Google Fonts:](https://fonts.google.com/)
    - Google fonts were used to import the 'Lora' and 'Source Serif 4' fonts into the style.css file which is used on all pages throughout the project.
1. [Font Awesome:](https://fontawesome.com/)
    - Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.
1. [Git](https://git-scm.com/)
    - Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.
1. [GitHub:](https://github.com/)
    - GitHub is used to store the projects code after being pushed from Git.
1. [Balsamiq:](https://balsamiq.com/)
    - Balsamiq was used to create the [wireframes](/assets/wireframes/Wireframes.pdf) during the design process.

## Testing

The W3C Markup Validator and W3C CSS Validator Services were used to validate every page of the project to ensure there were no syntax errors in the project.

-   [W3C Markup Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)
-   [W3C CSS Validator](https://jigsaw.w3.org/css-validator/#validate_by_input)

1.  Index page html validated.
![Index Validated](/assets/images/htmlValidatorIndex.png)
2.  Video page html validated.
![Video Validated](/assets/images/htmlValidatorVideo.png)
3.  Contact page html validated.
![Contact Validated](/assets/images/htmlValidatorContact.png)
4.  Thanks page html validated.
![Thanks Validated](/assets/images/htmlValidatorThanks.png)
5.  Css validated. The one warning is from the external bootstrap link.
![Css Validated](/assets/images/cssValidated.png)
![Css Warning](/assets/images/cssWarning.png)


### Testing User Stories from User Experience (UX) Section

-   #### First Time Visitor Goals

    1. As a First Time Visitor, I want to easily understand the main purpose of the site and learn more about the tutor.

        1. Upon entering the site, users are automatically greeted with a clean and easily readable navigation bar to go to the page of their choice.
        2. The main points are made immediately with the title.
        3. The user has two options, read what's on the homepage to learn more about the tutor, or
        click through to one of the other pages, to be inspired or contact the tutor.

    2. As a First Time Visitor, I want to be able to easily be able to navigate throughout the site to find content.

        1. The site has been designed to be fluid and never to entrap the user. At the top of each page there is a clean navigation bar, each link describes the page they will end up at clearly.
        3. On the Contact Us Page, after a form response is submitted, they are taken to a thankyou page,
        which has the same navbar as all the other pages, but also refreshes to the home page after 10
        seconds if no move is made by the user.

-   #### Returning Visitor Goals

    1. As a Returning Visitor, I want to find the best way to get in contact with the tutor with any questions I may have.

        1. The navigation bar clearly highlights the "Contact Us" Page.
        2. Here they can fill out the form on the page.
        3. The footer contains links to the organisations Facebook and Twitter page.
        4. Whichever link they click, it will be open up in a new tab to ensure the user can easily get back to the website.

-   #### Frequent User Goals

    1. As a Frequent User, I want to check to see if the inspirational video has changed.

        1. The user would already be comfortable with the website layout and can easily click the inspiration link.

### Further Testing

-   The Website was tested on Google Chrome, Internet Explorer, Microsoft Edge and Safari browsers.
-   The website was viewed on a variety of devices such as Desktop, Laptop, iPhone7, iPhone 8 & iPhoneX.
-   A large amount of testing was done to ensure that all pages were linking correctly.
-   Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

### Known Bugs

-   The font size for the header and footer is a bit smaller than I would like.

### Bugs that were fixed

-   There was a thin white gutter to the right of the header, and also the header and sections didn't line up properly. I fixed this by giving the section and header their own id and by setting the --bs-gutter-x to 0. I worked out this needed to be done by inspecting the css on chrome developer tools.
-   The code failed the html validator as I had used the same ID twice. I fixed this by changing the ID names.
-   The social links in the footer had a clickable area that was wider than the icon. This was poor UX. I tried changing the width of the anchor tag, but it didn't work. I then discovered on a forum that to change the width of an anchor tag you have to set the display to inline-block. It then worked.
-   The image was leaving white space below it on the index.html page when the screen width was between 1100px and 768px. I fixed this by reducing the font size in the main section of the page.
- The image was leaving white space to the right of it as the screen width got larger than 2160px. I fixed this by increasing the width of the img tag.

### Screenshots

1. index.html desktop and mobile.

![index.html desktop](/assets/images/indexDesktop.png)
![index.html mobile top](/assets/images/indexMobileTop.png)
![index.html mobile bottom](/assets/images/indexMobileBottom.png)

2. video.html desktop and mobile

![video.html desktop](/assets/images/videoDesktop.png)
![video.html mobile top](/assets/images/videoMobileTop.png)
![video.html mobile bottom](/assets/images/videoMobileBottom.png)

3. contact.html desktop and mobile

![contact.html desktop](/assets/images/contactDesktop.png)
![contact.html mobile top](/assets/images/contactMobileTop.png)
![contact.html mobile bottom](/assets/images/contactMobileBottom.png)

4. thanks.html desktop and mobile

![thanks.html desktop](/assets/images/thanksDesktop.png)
![thanks.html mobile top](/assets/images/thanksMobileTop.png)
![thanks.html mobile bottom](/assets/images/thanksMobileBottom.png)

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/dave-reynolds-93/ci-project-1)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://dave-reynolds-93.github.io/ci-project-1/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/dave-reynolds-93/ci-project-1)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/dave-reynolds-93/ci-project-1)
2. Under the repository name, click "Clone or download".
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/dave-reynolds-93/ci-project-1
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/dave-reynolds-93/ci-project-1
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.

## Credits

### Code

-   [Bootstrap 5.3.2](https://getbootstrap.com/docs/4.4/getting-started/introduction/): Bootstrap Library used throughout the project mainly to make site responsive using the Bootstrap Grid System, and
also for styling.

-   I got the code for the navbar from the [Bootstrap Documentation](https://getbootstrap.com/docs/4.1/components/navbar/)

-   I got the code for the 10 second refresh on the thank you page from my mentor.

-   I got the code for the form on the contact.html page from the [Bootstrap Documentation](https://getbootstrap.com/docs/4.1/components/forms/)

-   I got the code for the video from [W3schools](https://www.w3schools.com/html/html5_video.asp)

### Content

-   All content was written by the developer.

-   The colours were picked using a tailorbrands blog post as inspiration: [Tailor Brands Blog Post](https://www.tailorbrands.com/blog/logo-color-combinations)

### Media

-   The image was created by the developer.

-   The inspirational video was made by Tomislav Jakupec on [Pixabay.](https://pixabay.com/)

### Acknowledgements

-   My Mentor for continuous helpful feedback.

-   Tutor support at Code Institute for their support.
