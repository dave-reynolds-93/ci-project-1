<h1 align="center">
    Maths Tuition With Dave, python3 -m http.server
</h1>
<h2 align="center">
    A tutoring Website
</h2>

<div align="center"> 
Maths Tuition With Dave is a tutoring site with the aim of attaining more students. It is aimed at parents of children studying maths, and also people studying maths. Features include information about the services, with easy navigation of multiple pages.
<br>
</div>

## Table of Contents
1. [**UX**](#ux)
    - [**Goals**](#goals)
        - [**Project Goals**](#project-goals)
        - [**Visitor Goals**](#visitor-goals)
        - [**Business Goals**](#business-goals)
    - [**User Stories**](#user-stories)
    - [**Design choices**](#design-choices)
    - [**Wireframes**](#wireframes)

2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies used**](#technologies-used)

4. [**Testing**](#testing)

5. [**Deployment**](#deployment)
    - [**How to run this project locally**](#how-to-run-this-project-locally)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Code**](#code)
    - [**Acknowledgements**](#acknowledgements)

7. [**Disclaimer**](#disclaimer)

## UX

### Goals

### Project Goals

The primary goal of Maths Tuition With Dave is to provide an easy to use, information giving site.
It has two target audiences. Parents of children studying maths, and people studying maths themselves.

### Visitor Goals

The central target audience for Maths Tuition With Dave are:
- Parents of children studying maths.
- People studying maths.
- People who are looking for extra maths help for either themselves or another.


User goals are:
- Find a tutor for myself or my child.
- Be able to navigate the site easily, find out what I need and make a confident decision.
- Learn what other customers thought through reviews.

The Maths Tuition with Dave site is a great way to meet these needs because:
- The website has been designed by the developer who has years of experience of tutoring maths.
- The navigation fits with conventions of well laid out sites of a similar nature.
- The tutor has plenty of reviews from old and current clients.

### Business Goals

The Goals of Maths Tuition With Dave are:
- Provide a professional online tutoring site that helps the user feel safe that this tutor is trustworthy.
- Expand the online presence and awareness of the tutor.
- Allow potential customers to get in touch with the tutor

#### User Stories

As a parent with a child studying maths, or someone studying maths I want:
1. The ability to easily learn about the tutor, and about the tutoring process and prices.
2. The ability to contact the tutor.
3. The ability to see what other customers have thought of the tutor.
4. The ability to easily understand how the site works, and be able to inuitively navigate the site.


### Design Choices

The overall feel of the game is one that is designed for children to enjoy. The following design choices were made with this in mind:

**Fonts**

- The primary font **Fredoka One** was chosen because it resembles the simple letters used in products made for pre-school children. It's likeness to fridge magnets for children is nostalgic for parents as well. 

- The secondary font **Bubblegum Sans** was chosen for its childlike qualities, while complementing the primary font nicely in style because it is more compact.

**Icons**

- All icons used were chosen for their obvious meaning and purpose so that they can be understood by everyone.

**Colours**

- The primary colour choices of dark and light blue for the logo, titles and text were chosen because they have a clean clear aspect while contrasting each other well.
- Other colours used in the project were taken from the trophy image sourced, using a colour picker in Photoshop to make sure all colours used were consistent across the entire project.

**Styling**

- Cards and container boxes were given rounded corners to continue the child friendly theme, many real life memory cards for children have corners like this. 
- Repeating the same rounded corner pattern throughout the page keeps consistency in design and maintains the feeling that all elements belong together. 

**Backgrounds**

- The background image of toy trains was chosen to give the feeling of playing the game in a child's playroom. 
- Specifically chosen because it is a "flat-lay" - a photograph taken from directly above - this means the background complements the game without distracting from it.
- The background images for the modals were chosen for their comic-book like qualities, adding a little positive emotional feedback at a level that appeals to a child. 

**Card images**

- Disney and Pixar characters were chosen for this game because they are recognised and loved by children. 
Cars characters were specifically chosen because it is extremely popular with boys, 
the Frozen characters because they are very popular with girls, 
and the Toy Story Characters because they appeal to both girls and boys. 

**Audio files**

- To continue the feeling of a game made for children, clicking button sounds were added that are similar to the sounds a child might hear when operating a physical toy with buttons. 
- The card flipping sounds and "bing" on a correct match were added to give positive feedback on use of the game. 
- The sound of applauding children played on completing the game was chosen because it appeals most to children, and again fits within the theme of PicFlip!

### Wireframes

These wireframes were created using [Balsamiq](https://balsamiq.com/) during the Scope Plane part of the design and planning process for this project. 

- [User info modal](https://i.ibb.co/FWBy68Q/Create-profile.png)
- [Game page](https://i.ibb.co/H2XtCW9/Game-page.png)
- [Win pop-up](https://i.ibb.co/5809P3Q/Win-popup.png)

## Features
 
### Existing Features

1. **Player info modal**
    - On arriving at the page for the first time, this modal pops up to collect the players name and their choice of avatar image from the three available. 
    - This modal is also activated if stored player data is reset. 
    - The modal has been programmed to not close unless both the name has been filled out at an avatar has been chosen. Tooltips appear to guide the user to enter both.
    - The default setting for modals that they can be closed if clicking on the modal background has also been disabled for this modal specifically.  

<div align="center">
<img src="https://i.ibb.co/NpXs3QC/user-info-modal.jpg" alt="Screenshot: User info modal" >
</div>


2. **Dashboard**
    - The game dashboard contains the player info display, difficulty selection, character selection, info, mute and reset buttons. 
    - On mobile devices a chevron arrow is displayed to tell the player to scroll downwards to the game board. 

<div align="center">
<img src="https://i.ibb.co/pwn3GFV/game-board.jpg" alt="Screenshot: Game board"><br>
<img src="https://i.ibb.co/JFr93rH/mobile-view-dashboard.jpg" alt="Screenshot: dashboard mobile view" >
</div>

3. **Player info display**
    - At the top of the dashboard the players name is displayed with their chosen avatar. 
    - Underneath this is the display to show their highest score (out of 5 stars) for the currently selected difficulty level. 
    - The star display changes if a different level is selected. 

4. **Difficulty selection buttons**
    - Players can select from three difficulty levels: Easy (8 cards), Medium (12 cards) and Hard (16 cards).
    - The difficulty buttons are coloured green, yellow and red for users who can't read to tell them apart.
    - Selecting any of these buttons turns any face-up cards back over and reshuffles the cards.

5. **Character selection buttons**
    - Players can choose from three different Disney movie characters to display on the memory cards.
    - Selecting any of these buttons turns any face-up cards back over and reshuffles the cards.

6. **Mute button**
    - The mute button switches off all audio in the game. It is represented by a large speaker icon, which switches to one with a cross next to it when active.
 
7. **Reset button**
    - The reset button, represented by a curved arrow, resets the game, when it is pressed the game turns any face-up cards back over, reshuffles them and resets the turns counter back to 0. 
    - It does not reset the difficulty level or characters chosen for the cards. 

8. **Info button**
    - Represented by a large question mark, the info button opens the info modal. 
    - The info modal offers easy to understand instructions on how to play the game. 
    - Underneath how to play instructions there is information on how to open the modal to delete the player’s profile. 
    - The place to click is easy for an adult to see, but not an obvious button to click for a child. 

<div align="center">
<img src="https://i.ibb.co/xJ7PbS2/info-modal.jpg" alt="Screenshot: Info Modal" >
</div><br>

9. **Parental check modal**
    - This modal appears if the correct icon is clicked in the info modal. 
    - It explains that deleting the player profile will remove all game data including high scores. 
    - Then it asks a simple maths question with 9 possible answers to choose from, only if the correct answer is clicked will the player profile be deleted. 
    - All other choices will close the modal when clicked with no further effects to the game.
    - At this point the maths question and correct answer are static. This is a feature I would like to update in the future (see [Features Left to Implement](#Features-left-to-implement) for more information)

<div align="center">
<img src="https://i.ibb.co/nrRkQsq/delete-data-modal.jpg" alt="Screenshot: Parental check modal" >
</div>


10. **Turns counter**
    - Located above the game cards, the turns counter counts the number of turns the player has taken in the current game. 
    - This total is then used to give the player a score out of 5 stars when the game is complete.

11. **Game board and cards**
    - The game board is where the memory cards are displayed. 
    - The cards are laid out in a grid 4 cards wide on medium to large screens, and 3 cards wide on phones to allow the size to remain easy for young fingers to tap on.
    - The number of rows of cards visible changes depending on the difficulty level selected. 

<div align="center">
<img src="https://i.ibb.co/q5sDjB4/mobile-view.jpg" alt="Screenshot: game board mobile view" >
</div>


12. **Win modals** 
    - PicFlip! has two possible win modals that pop up when a game is completed. 
    - Both win modals display the number of stars the player won for the game they just played.
    - The standard win modal is launched if the player completed the game, but did not beat their previous high score.
    - The high score win modal is launched for a new high score, along with the number of stars earned the high score win modal also displays a trophy picture.

<div align="center">
<img src="https://i.ibb.co/YRjzhw5/high-score-modal.jpg" alt="Screenshot: high score modal" >
</div>


13. **Footer tab**
    - A small tab is displayed at the bottom of the website that when clicked pulls up a short footer with developer information on. 

### Features Left to Implement

1. **Improvements to the parental check modal**

In the future more functionality can be added to the parental check modal to: 
    - Randomize the math question and active number to click to prove you are an adult. 
    - if the incorrect answer is given the math question/answer is randomised again. 
    - If the incorrect choice is made 5 times in a row then the modal closes. 

2. **Additional difficulty level**
    - Add level "insane" for older kids to try. 
    - This would only be possible on mobiles if converted into a mobile app, as the full screen would be needed to make enough room for all the cards.

3. **Conversion to a mobile App**
    - If this project were to become commercial the current card pictures would have to be changed to ones commissioned specifically for it, rather than using Disney images.

## Technologies Used

- This project uses HTML, CSS and JavaScript programming languages.
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Cloud9](https://c9.io) 
    - Developer used **Cloud9** for their IDE while building the website.
- [Bootstrap](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap** to simplify the structure of the website and make the website responsive easily.
    - The project also uses Bootstrap to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to style the website fonts.
- [Imgbb](https://imgbb.com)
    - All external images for this project are stored on **Imgbb.com**.
- [Jasmine](https://jasmine.github.io/)
    - This project used **Jasmine** to automatically test all JavaScript and jQuery code.
- [Jasmine-jQuery](https://github.com/velesin/jasmine-jquery)
    - This project used **Jasmine-jQuery** CDN to make it possible to test jQuery code using Jasmine.
- [GitHub](https://github.com/)
    - This project uses **GitHub** to store and share all project code remotely. 
    - The new GitHub Projects planner was utilised to plan and keep track of this project. This project plan can be viewed [here](https://github.com/AJGreaves/picflip/projects/1).
- [Photoshop](www.adobe.com/Photoshop)
    - This project used tools in **Photohshop** to edit, crop and save images as well as ulitising the colour picker to ensure color consistency over the entire project.
- [Browserstack](https://www.browserstack.com/)
    - The project used **Browserstack** to test functionality on all browsers and devices.
- [AutoPrefixer](https://autoprefixer.github.io/)
    - The project used **AutoPrefixer** to make sure all css prefixes were the most up to date versions. 

## Testing 

1. When I initially setup the project, I copied the code institute template url, instead of using it to create my own repository. I realised I was pushing to the template repository instead of my own project repository. I then created my own project repository using the code institute template, and now can push to my own repository.

## Deployment

This project was developed using the [Cloud9 IDE](https://c9.io), committed to git and pushed to GitHub using the built in function within cloud9. 

To deploy PicFlip! to GitHub Pages from its [GitHub repository](https://github.com/AJGreaves/picflip), the following steps were taken: 
1. Log into GitHub. 
2. From the list of repositories on the screen, select **AJGreaves/picflip**.
3. From the menu items near the top of the page, select **Settings**.
4. Scroll down to the **GitHub Pages** section.
5. Under **Source** click the drop-down menu labelled **None** and select **Master Branch**
6. On selecting Master Branch the page is automatically refreshed, PicFlip! is now deployed. 
7. Scroll back down to the **GitHub Pages** section to retrieve the link to the deployed website.

The PicFlip project made use of several branches for development, testing and bug fixing. 
The Master Branch has always been the one deployed to GitHUb Pages. When displaying the website life, the developer tries to keep the master branch to optimal code only.
At the moment of submitting this Milestone project the Development Branch and Master Branch are identical. 

### How to run this project locally

To clone this project from GitHub:
1. Follow this link to the [PicFlip GitHub repository](https://github.com/AJGreaves/picflip).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your local IDE open Git Bash.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on cloning a repository from GitHub [here](https://help.github.com/en/articles/cloning-a-repository).

## Credits

### Content

- All text in this project was written by the developer.

### Media

#### Images
- The PicFlip logo was created using [Hatchful](https://hatchful.shopify.com).
- The Trophy image used was sourced from [Kissping](https://www.kisspng.com).
- The images for the user avatar were sourced from [Pngtree](https://pngtree.com).
- The images used for the memory cards were obtained from [Google Images](https://www.google.com/imghp?hl=en) and are used for educational purposes only. 
Copyright for the memory card images belong to [Disney](https://www.thewaltdisneycompany.com/) and [Pixar](https://www.pixar.com/).
- The comic-book style modal backgrounds were sourced from [freepik](https://www.freepik.com)
- The game board background photograph was obtained from [Jason Leung on Unsplash](https://unsplash.com/photos/M55JcA9wOG0).

#### Audio
- The audio file for button click sound was sourced from [SoundJay](https://www.soundjay.com).
- The audio files for card flip sound, matched cards sound and children applauding were sourced from [FreeSound](https://freesound.org/).

### Code
- Code for the card flip animation taken from this [W3Schools](https://www.w3schools.com/howto/howto_css_flip_card.asp) post.
- Box shadow codes were generated at [CSS matic | box-shadow](https://cssmatic.com/box-shadow).
- Code for filtering through an array for specific values sourced from this [StackOverflow](https://stackoverflow.com/questions/6120931/how-to-count-the-number-of-certain-element-in-an-array) post.
- Code for making images into radio buttons sourced from this [StackOverflow](https://stackoverflow.com/questions/17541614/use-images-instead-of-radio-buttons) post.
- Code for adding the correct prefixes to css was created using [AutoPrefixer](https://autoprefixer.github.io/).
- Function to toggle text in the pull up tab from push to pull taken from this [StackOverflow](https://stackoverflow.com/questions/2155453/jquery-toggle-text) post.

### Acknowledgements

Special thanks to: 
- Code Institute Mentor Simen Daehlin for his time and support in explaining and demonstrating areas of code this developer was struggling to understand.
- Alumni John Longgately and Robin Zigmond for their help in guiding this developer in understanding JavaScript, jQuery and Jasmine testing. 
- Owen (4) and Declan (9) who tested the game play extensively, and offered advice on what would make it more fun for them to play.

#### Disclaimer
The content of this website, including the images used, are for educational purposes only.

### A note to my fellow Code Institute students

I am happy that you have come to look at my readme as an example of how to write a good one for your second Milestone project. You are welcome to learn how to structure and format your own readme from mine.

However, it is not ok to copy and paste large portions of it into your own project. Please remember to write your own readme yourself, rather than copying mine or someone elses.

Many thanks! Anna