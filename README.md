# Responsive Web Layout
*This project was completed as part of an immersive code academy cirriculum.* 

## Creating a Responsive Layout
* Responsive web design (RWD) has quickly become a standard practice, in large part due to the explosion of different devices that have web browsing capabilities.

### Let's consider some of those devices:
#### Smart Phones
* Small hand held devices with high pixel density screens. 
* They are narrow and tall and don't allow for widely varying page layouts. 
* Users interact by touching the screen.

#### Tablets 
* Slightly larger than a smart phone
* They are often rotated to a "landscape" (on its side, so to speak) orientation for viewing things like movies. 
* People often use them to read text heavy content like books and articles. 
* Tablets are also touch screen devices, just like smart phones.

#### Desktop Monitors
* Large and almost always horizontal. 
* They have a lower pixel density (think 'resolution') 
* Users interact in a variety of ways. 
   * Some desktop computers have touch screens, many do not. 
   * Most users interact with desktop computers via a mouse and keyboard.
   
All of these devices have web browsers that can access websites. This presents a problem for any web designers who want their designs to function well on all of those devices.


## The Elements of Responsive Web Design
Responsive Web Design has two interdependent elements:
* Media Queries
    * Media queries are CSS statements that allow us to contextualize styling.
    * Have breakpoints 
* Fluid Layouts
    * Used to manage what happens between the media queries. 
    * Creates a fluid transition when your screen size changes instead of a stark jump from desktop to mobile view

## Breakpoints
* The term "breakpoint" refers to the **pixel width** where the styles change. 
* You can think of it as saying: "Breakpoints specify when one layout "breaks" into a new layout".
* When developers refer to breakpoints, they are referring to the **pixel widths in their media queries.**

#### Common Breakpoints
Practically speaking, most sites have media queries for three sizes:
1. mobile (or "small", like an iPhone), 0-639px
2. tablet (or "medium", like an iPad), 640px - 1024px
3. desktop (or "large", like a computer), 1025px and up

* Those three "sizes" require two breakpoints:
    * 640px 
    * 1025px

## Fluid Layouts
* Even with media queries, the experience of using sites can be a little clunky if we don't manage what happens between the media queries. 
* Fluid layouts help manage the user's experience as they transition between screen sizes or re-size their browser window


