# Agnes Strand Photography

The Agnes Strand Photography website is made with the purpose of showing collegues and potential customers the work of the photographer, give a professional first impression and a clear display of the information and the content.

The goal was to really combine the photographer's art and clear information to the point that the photographer wants to use it as her own in the future. The agreement I have with the photographer is to implement JavaScript once I have learned it to make the images more interactive and the website feel even more alive. 

![Responsive Mockup](https://github.com/telljacob/project-one/blob/main/assets/images/amiresponsive.png?raw=true)

## Features

### Navigation

In the navigation bar we can use the link to: Home, Gallery, Services, About and Contact to navigate ourselves around the website to the different pages. The header has a fixed position to help easily navigate around the site wherever you are lower on the respective pages. Both the header and the footer has a different opacity value on the frontpage to give the background image even more depth.

**Front Page**
![Nav Bar Frontpage](https://github.com/telljacob/project-one/blob/main/assets/images/headertwo.png?raw=true)

**All Other Pages**
![Nav Bar](https://github.com/telljacob/project-one/blob/main/assets/images/header.png?raw=true)

### Frontpage Background Image with animation
The Frontpage image took a long time to decide on. The photographer isn't a nature photographer. A dramatic mountain range was my first thought but it would very poorly represent what the photographer does. A "fashion" magazine cover background for example would bring too much emphasis on that particular image, it had to be more neutral. This became the middle ground solution. It's a neutral and very calming image which is originally in black and white aswell, I didn't need to alter the image to create what I wanted the background to.

![Background Page](https://raw.githubusercontent.com/telljacob/project-one/main/assets/images/ida-two.webp)

### Social Media Links
Links to the photographer's Social Media, opens in a new page and is also the preferred way for the photographer to get in contact with, which lead to the decision of having the footer visible at all times.

![Social Media in Footer](https://github.com/telljacob/project-one/blob/main/assets/images/socialmedia.png?raw=true)

### Photo gallery
The photo gallery is the photographer's own selected work, the order of presentation is my own design. They are divided into three responsive columns that becomes one on smaller screen sizes.

![Picture of Gallery](https://github.com/telljacob/project-one/blob/main/assets/images/photogallery.png?raw=true)

### "Services" Page
The kind of work the photographer offers is listed on its own page to keep the "business" to one page. This is to let the rest of the page be a display of the photographer's creativity with having as much focus as possible on the previous work

### "About The Photographer" Page
To show the person who created the work displayed and give a short introduction, enough for the user to know who they would be contacting if they were to do so. You don't want to do business with someone you know nothing about either, some personal information such as interests is important. For an aspiring model this is even more vital as the quality of the work is a reflection of how you can work together. Being comfortable in front of the camera means you need to be comfortable with the person behind it.


### "Contact Information" Page
To shortly and concicely provide the contact information alongside a professional portrait.


## Validator Testing

I have tried the website on Chrome, Safari and Firefox.

HTML - W3C Validator: No errors

CSS - Jigsaw Validator: No errors

**Lighthouse score Home Page**

![Lighthouse Score](https://github.com/telljacob/project-one/blob/main/assets/images/lighthousescore.png?raw=true)

**Lighthouse score Gallery Page**

![Lighthouse Score Gallery](https://github.com/telljacob/project-one/blob/main/assets/images/lighthousescoregallery.png?raw=true)

## Challanges

### Image Integrity
The fact that these images individually are created with such purpose. To crop, change color or anything else would alter the emotion the image was meant to give. A made an extra effort to avoid cropping any images used in the gallery. However, after learning more about image rendering in html I've learned that I should've changed the width of all images to be the same. This would significantly improve the performance. To additionally improve user experience I would have considered having all the images not being displayed immediatly to start loading on scroll. I now know that is possible. Having 30 images load at the same time is simply too much to ask while still avoiding performance issues.   

### Gallery rendering and performance
With the focus of the project being to display pictures I wanted a large photo gallery to display the best work of the photographer. The first step was to render all images down from being over 5000px down to 720px. I could probably have gone lower to improve performance but I didn't want the quality of the images to be affected noticably. After all, the purpose of the website is to show the work of the photographer.

The first mistake was to use the same strategy as I was taught in the Love Running project, having a section with columns where the pictures are automatically place in and resized. The response rate of the website was up to 10 seconds before the pictures eventually fell into place. So I wanted a solution that didn't distract the user with images jumping around. I decided to divide the images into three seperate columns by default and choose myself which picture goes where. This lead to the images rendering where I wanted them even if all the images didn't load instantly.

The other mistake was to convert the images to png instead of webp from the start. However, it lead me down a path of image display optimization, looking back at it I learned a lot from the mistake.

### Full Size Frontpage Image
This was something I hadn't done before but I was determined to make it on my own without research. Eventually it fell into place after a lot of trial and error. Mostly learning about relative/absolute positioning and nesting divs. I now feel much better equipped going forward in my studies.

## Technical difficulties in development
- Workspace was not able to load, contacted support and got sorted eventually after doing a complete reset of the workspace dashboard.
- The site was during parts of the development not able to load properly in Chrome where parts of the page was grey. This bug eventually stopped later down the line of development. Cause unknown.

## Credit
The use of image zoom is not my own creation. I could not remember how it was implemented so I copied the syntax from the Love Running project from earlier in the course.
