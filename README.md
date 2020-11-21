# Blue Dolphin Tours

![Device Showcase](https://github.com/reidycolm/MS1-Project/blob/master/assets/img/blue-dolphin.png "Blue Dolphin Tours Responsive")

### View the live project [here.](https://reidycolm.github.io/MS1-Project/index.html)

This is my first project as a Code Institute student. I decided to create a website for a fictitous business that specialised in boat tours along the Wild Atlantic Way. Because a service of this kind would attract customers of all ages and backgrounds, I thought it was very important to create a page that was easy to navigate and minimilist in its design.
 
## UX
 
#### First Time Visitor Goals
    1) I want to know immediately what the website is about when I load the page.
    2) As I may be a tourist, it's very important that I can easily see pictures of where the tours operate so I know if I would like to vist them or not.
    3) I want to easily be able to access the website on any device as more than likely I will not have my laptop when I am travelling.

#### Returner Visitor Goals
    1) It's very important that I'm able to get in touch with the tour company as I may need to contact them with questions about the tours I'm booked onto.
    2) I want to be able to follow Blue Dolphin on social media so I can see recent updates and check out reviews from other tourists.
    3) As I may be returning to the site beause I'm having trouble deciding what tour to choose, I want to be able to easily compare what exactly is involved in each.

#### Design

* **Colour Scheme** - The primary colours used were steelblue and white. I chose these as I feft artistically they worked quite well and steelblue was very similiar to an ocean colour which I thought was sutible.

* **Typography** - The font style used on this project was Lora which I sourced from Google Fonts.

* **Images** - I picked three clear, large images to use in the carousel slider. I wanted the person visiting the site to immediately be drawn to them and become aware that they were the locations that the tours were based on.

* **First Sketch** - [Sketch](assets/img/sketch.jpg)

* **Large Screen Devices**
    - [Homepage](assets/img/large-home.png) 
    - [Tours](assets/img/large-tours.png)
    - [Contact](assets/img/large-contact.png)

* **Small Screen Devices**
    - [Homepage](assets/img/small-home.png) 
    - [Tours](assets/img/small-tours.png)
    - [Contact](assets/img/small-contact.png)


## Features

* **Navigation Bar** - Located at the top of every screen, it provides easy access to the other pages of the website. Appears as dropdown button on smaller devices. Each link and logo in the nav bar can be clicked.

* **Image Carousel** - Sliding Images showcase the locations of the tours Blue Dolphin offers. Also includes indicators so the person has full control of moving onto the next photo.

* **Buttons** - Used to link to tours.html and to ensure a modal pops up when "book now" is clicked. Each button changes style when hovered over or clicked.

* **Modal** - Appears as a pop up when "book now" is selected and acts as a notification to users to convey that the business is currently closed due to the pandemic.

* **Contact Page** - Provides the ability to send the business a message. Name and Email field are required, otherwise it will not allow you to complete form.


## Technologies Used

#### Languages

* [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
* [CSS3](https://en.wikipedia.org/wiki/CSS)

#### Frameworks, Libraries and Other Tools

* [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction)
    - Used to style webpage and ensure it was fully reponsive

* [JQuery](https://jquery.com)
    - In the form of js scripts which allowed for carousel images to slide and clickable drop down nav bar to function.

* [Gitpod](https://gitpod.io/)
    -   Gitpod was the IDE I used when making this project

* [Git](https://git-scm.com/)
    - Used for version control and allowed me to save my changes externally by committing to GitHub

* [Github](https://github.com/)
    -   Was used to store files of the project that I had pushed using Git & Gitpod

* [Pixlr](https://pixlr.com)   
    - Online photo editor I used to make sure carousel images were the correct size.

* [Font Awesome](https://fontawesome.com/)   
    - Site used to soruce icons for the webpage.

* [Google Fonts](https://fonts.google.com/)   
    - Used to select font styles       

* [Lighthouse](https://developers.google.com/web/tools/lighthouse)   
    - Lighthouse is an open-source, automated tool for improving the quality of web pages. You can run it against any web page, public or requiring authentication. It has audits for performance, accessibility, progressive web apps, SEO and more.     


## Testing

#### First Time Visitor Goals
    1) Backdrop container on index.html explains purpose of website and gives option to book tour quickly.
    2) Carousel slider used shows images of the tours we offer. Tourists would be able to identify and recognise the places they want to travel to.
    3) Website is fully responsive and works on any kind of device.

#### Returner Visitor Goals
    1) Backdrop container on index.html explains purpose of website and gives option to book tour quickly.
    2) Carousel slider used shows images of the tours we offer. Tourists would be able to identify and recognise the places they want to travel to.
    3) Website is fully responsive and works on any kind of device.

#### Validators

* **HTML**
    - [Homepage](assets/img/htmlval.png) 
    - [Tours](assets/img/htmlval2.png)
    - [Contact](assets/img/htmlval3.png)

* **CSS**
    - [style.css](assets/img/cssval.png) 


#### Lighthouse 

* **Large Screen Devices**
    - [Homepage](assets/img/home-test.png) 
    - [Tours](assets/img/tours-test.png)
    - [Contact](assets/img/contact-test.png)

* **Small Screen Devices**
    - [Homepage](assets/img/small-test-home.png) 
    - [Tours](assets/img/small-testtour.png)
    - [Contact](assets/img/small-testcontact.png)

 #### Manuel Testing 

All of the following were tested extensively on multiple devices using dev tools and different phones/computers in the household:

* **NavBar** - Made sure it was reponsive and that dropdown menu worked. Had issue on tours.html and contact.html where it wouldn't work but figured out I never linked js scripts at bottom of file.

* **Carousel** - At first the images didn't fit together on the carousel. It would change size after every slide so I used the pixlr to edit and crop.

* **Contact-Form** - Form won't allow you to submit unless you have filled in both of the email and name containters.

* **Buttons** Tested each button to ensure they change style when hovered on or clicked and each link to either a pop up modal or the tours.html page

* **Social Media Icons** - Icons have been tested to make sure external links work and open in new tab when clicked.

## Deployment

### GitHub Pages

The project was deployed to GitHub Pages using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/sreninc/grow-yourself)
2. At the top of the Repository (not top of page), locate the "Settings" Button on the menu.
    - Alternatively Click [Here](https://raw.githubusercontent.com/) for a GIF demonstrating the process starting from Step 2.
3. Scroll down the Settings page until you locate the "GitHub Pages" Section.
4. Under "Source", click the dropdown called "None" and select "Master Branch".
5. The page will automatically refresh.
6. Scroll back down through the page to locate the now published site [link](https://sreninc.github.io/grow-yourself/) in the "GitHub Pages" section.

### Forking the GitHub Repository

By forking the GitHub Repository we make a copy of the original repository on our GitHub account to view and/or make changes without affecting the original repository by using the following steps...

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/sreninc/grow-yourself)
2. At the top of the Repository (not top of page) just above the "Settings" Button on the menu, locate the "Fork" Button.
3. You should now have a copy of the original repository in your GitHub account.

### Making a Local Clone

1. Log in to GitHub and locate the [GitHub Repository](https://github.com/sreninc/grow-yourself)
2. Under the repository name, click the "Code" button and a dropdown menu will appear.
3. To clone the repository using HTTPS, under "Clone with HTTPS", copy the link.
4. Open Git Bash
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type `git clone`, and then paste the URL you copied in Step 3.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
```

7. Press Enter. Your local clone will be created.

```
$ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY
> Cloning into `CI-Clone`...
> remote: Counting objects: 10, done.
> remote: Compressing objects: 100% (8/8), done.
> remove: Total 10 (delta 1), reused 10 (delta 1)
> Unpacking objects: 100% (10/10), done.
```

Click [Here](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/cloning-a-repository#cloning-a-repository-to-github-desktop) to retrieve pictures for some of the buttons and more detailed explanations of the above process.


## Credits

### Content

* [Bootstrap](https://getbootstrap.com/docs/4.4/getting-started/introduction)
    - Read documentation and took code from site to use for carousel, modal and cards on tour page.

* [Youtube Video](https://www.youtube.com/watch?v=w4xa_u80qF4&t=309s)
    - Watched and used code used in this video to make a responsive contact form.

* Rewatched Projects from course. Took inspiration and advice used in Whiskey Drop mini project.


### Media

* [All of the images used in this project were taken from Google Images searches](https://www.google.com/imghp?hl=EN)
