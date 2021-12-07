# Welcome to Krusboda

The welcome to Krusboda website is an informative site providing useful information about the residential area of Krusboda in Stockholm, Sweden. Users could for example be residents, visitors or potential home buyers in the area.

Users of this website will be able to find useful information about the area, as well as imagery to help them get an insight of what it’s like there.

## Design

The main design idea is simple and elegant with a consistent theme on colors and headings. The website is intended to give a calm visual impression with clear information and not too many pictures.

* ### Colour Scheme 
The main color scheme is white and dark gray #383232 throughout the website.

* ### Typography
The Nunito Sans font is the main font used on the texts throughout the whole website while Leckerli One is used for headings. Nunito Sans is a simple and clean font that is easy to read. This makes a nice contrast to the headers since Leckerli One is an eye-catching and playful font with irregular brush shapes.

* ### Imagery
The images on the Start/Home page are carefully chosen to match each other in color and style. They provide a harmonious feeling reminiscent of summer, water & forest in muted colors of light blue, gray & green.

* ### User/Visitor goals

As a user, I want to easily understand the main purpose of the site and learn more about the area.

As a user, I want to be able to easily navigate throughout the site to find content.

As a user, I want to be able to look at pictures to get a sense of what it is like to visit the area.

As a user, I want to see a map of the area so I can navigate there. 

As a user I might want to get in touch with the person in charge of the website.

## Wireframes

Attached below is a picture of my wireframe or program blueprint, a visual guide that represents the skeletal framework of how I planned out the project.

![Wireframes](screenshots/wireframes_html.png)

## Features

### Navigation
Featured at the top centre of the page, the navigations shows four options: Home (takes user back to the home page), About, History and 
Gallery. Each option is illustrated by a font awesome-icon to make them easier to distinguish. 

The navigation menu is in a font that matches the rest of the page’s body text and in the same dark grey color. 

The section that the user is currently visiting is underlined for easy overview.

When hovered, the links to the other pages are underlined so that the user knows they are clickable links.  

![Navigation menu](screenshots/navigation.png)

### Header
The header shows the words ”Welcome to Krusboda” in a dark grey color on a background image of a view overlooking some houses and forest and a cat in the foreground.

![Header](screenshots/header.png)

### Home page
The homepage consists of the main header that is in the same color but a contrasting font than the body text to make it stand out. 

Under the main header and image there are three smaller headers that read: ”Built in 1970-75”, ”Surrounded by nature” and ”A great community”, in the same font and color but smaller.

Under each header there is an image to illustrate and create context. Under each image is a short piece of text that explains something about the area relating to the image. 

The purpose of this section is to give the users an idea of what the area is like and to make them curios about finding out more.  

![Home page preview](screenshots/home_responsive.png)

The home page also shows a footer that ontains an embedded google map that shows the location of the area. 

The footer also contains copyright info and a hyperlink that allow users to send an email to the site owner.

![Footer](screenshots/footer.png)

### About page
Takes the user to an article which describes the area and general facts about it, with illustrating images. 

The purpose of this section is to provide information to those interested and give a more extensive picture of the area than is suitable on the home page.

![About page preview](screenshots/about_responsive.png)

### History page 
Takes the user to an article which describes the historical facts surrounding the area, also with illustrating images like in the ”About”-page.

The purpose of this section is to provide information to those interested in finding out more and learn about the history of the area.

![Home page preview](screenshots/history_responsive.png)

### Gallery page
Takes user to a gallery with images and videos portraying the area. 

When hovered the images scale up to 1.5 size and also show a descriptive text inside the image.

The purpose of this is to showcase the area and it’s pleasant surroundings.

![Home page preview](screenshots/gallery_responsive.png)

## Testing

The website works in the following browsers:
Chrome, Firefox, Safari.
The project is responsive, functional and looks good in all of the standard screen sizes available in devtools.

I have confirmed that the mailto-link works, as well as the video control actions.

## Testing User Stories from User/Visitor Goals Section

When entering the site, users are greeted with a clean and easily readable navigation bar in the middle top of the page to go to the page of their choice. The navigation bar is visible at the top of each page.

Underneath the navigation bar is a Hero Image with the text ”Welcome to Krusboda”.

Below the ”Welcome” image the main points of the site are shown in ”info-boxes” with illustrating images and a short, descriptive text.

On the pages ”About” and ”History” the user can read articles containing relevant information about the area.
 
The gallery page has a number of images and videos so the user can get a better understanding of the area.

In the Home page footer there is a Google map of the area so the user can navigate there. 

In the Home page footer there is a mail to-link so that the user can get in touch with the person in charge of the website.

## Bugs

When deployed to GitHub Pages I discovered that one of the images in the gallery did not load properly. This was because the image file was very large. I therefore decided to convert all of my images from .jpeg to .webp to make them smaller and to make the website load faster.

## Validator testing
No errors were returned when passing through the official W3C validator. 

No errors were returned when passing through the official (Jigsaw) validator. 

## Accessibility
I confirmed that the colors and fonts chosen are easy to read and accessible by running it through lighthouse in devtools.

![Lighthouse score](screenshots/lighthouse_score.png)


## Deployment
The site was deployed to GitHub Pages (GitHub repository > settings, select branch main and click save). 

The live link can be found [here](https://jossansik.github.io/Portfolio-project1/)

## Credits

The code for the gallery page is in large parts derived from the Code Institute course materials.

I have based the scaling hover effect on the gallery images on the following [code](https://codepen.io/ran0904/pen/bNpLvX).