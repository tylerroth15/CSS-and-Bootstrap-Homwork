# CSS-and-Bootstrap-Homwork

# My Portfolio Page Creation

In this homework assignment, I was tasked with creating a mobile responsive portfolio that we will link our future projects in an effort to showcase all of the work and skill sets that we are learning to utilize through the duration of this course. 

### Layout

### Bootstrap

Utilizing Bootstrap, I was able to develop my portfolio site to include the following:
1. Nav Bar
2. Responsive Layout
3. Responsive Images
4. A Sticky Footer
5. Card layouts that was used on both the about page and the portfolio page
6. Contact form

### Font-Awesome 

Utilizing Font-Awesome, I was able to style out and link my social media profiles in the sticky footer that I created.  I linked the following to my portfolio website:
1. Facebook
2. LinkedIn

### Design
Overall, the design is based off the homework examples given. However, I did change the shape of my profile picture and added a texted background to help the overall website have more personality. You can find the HTML and CSS that was used to achieve this design. 

#### Profile Picture HTML

<img src= “” alt= “” class= “img-fluid rounded-circle float left float-sm-left float-md-left float-lg-left float-xl-left p-5” style= “width: 300px;height: 300px;”>

#### Textured Background CSS

body{
background-image= url (“”);
background-color: #cccccc;}

### Media Queries

Bootstrap helps with the mobile responsive layout of the page but I did need to add a few media queries to help with the breakpoints and they page layouts. I applied the following media queries to my CSS. 

##### mobile device 
@media only screen and (min-device-width : 320px) and (max-device-width : 480px) {
    img{
        width: 100%}
}

##### tablet/ipad 
@media only screen and (min-device-width : 768px) and (max-device-width : 1024px) {
    img{ width: 100%}
    }

##### laptop and desktop
@media only screen  and (min-width : 1224px){
}

##### large screen 
@media only screen  and (min-width : 1824px) {
}