# Agnes Strand Photography

The Agnes Strand Photography website is made with the purpose of showing collegues and potential customers the work of the photographer, give a clean first impression and a clear display and overview of information.

The combination of art and to provide clear information to the point that the photographer wants to use it as their own is the goal of the wesite. 

![Responsive Mockup](https://github.com/telljacob/project-one/blob/main/assets/images/amiresponsive.png?raw=true)

## Features

### Navigation

In the navigation bar we can use the link to Home, Gallery, Services, About and Contact to navigate ourselves around the website to the different pages.

![Nav Bar](https://github.com/telljacob/project-one/blob/main/assets/images/navbar.png?raw=true)

### Landing image

![Background Page](https://raw.githubusercontent.com/telljacob/project-one/main/assets/images/ida-two.webp)

### Social Media Links

![Social Media in Footer](https://github.com/telljacob/project-one/blob/main/assets/images/socialmedia.png?raw=true)

Links to the photographer's Social Media, opens in a new page and is also the preferred way for the photographer to get in contact which lead to the decision of having the footer visible at all times.

### Photo gallery

![Picture of Gallery](https://github.com/telljacob/project-one/blob/main/assets/images/photogallery.png?raw=true)

The photo gallery is the photographer's own selected work. They are divided into three responsive columns that becomes one on smaller screen sizes.

### Services Section

The kind of work the photographer offers is listed on its own page to keep the "business" to one page. This is to let the rest of the page be a display of the photographer's creativity with having as much focus as possible on the previous work

### About The Photographer Page

To provide the background of the person who has created the work displayed.


### Contact Information Page

To shortly and concicely provide the contact information alongside a professional portrait.


## Validator Testing

HTML - W3C Validator

CSS - Jigsaw Validator

Lighthouse test:

![Lighthouse Score](https://github.com/telljacob/project-one/blob/main/assets/images/lighthousescore.png?raw=true)

## Challanges

### Gallery rendering and performance
With the focus of the project being to display pictures I wanted a large photo gallery to display the best work of the photographer. The first step was to render all images down from being over 5000px down to 720px. I could probably have gone lower to improve performance but I didn't want the quality of the images to be affected noticably. After all, the purpose of the website is to show the work of the photographer.

The first mistake was to use the same strategy as I was taught in the Love Running project, having a section with columns where the pictures are automatically place in and resized. The response rate of the website was up to 10 seconds before the pictures eventually fell into place. So I wanted a solution that didn't distract the user with images jumping around. I decided to divide the images into three seperate columns by default and choose myself which picture goes where. This lead to the images rendering where I wanted them even if all the images didn't load instantly.

The other mistake was to not convert the images to webp instead of png.

### Full Size Frontpage Image

## Bugs

Workspace not being able to load, contacted support and got sorted eventually.

