# Exercise Collaborative HTML Website

> By Ovidio Santoro and Keili Rosales

## Objective

The exercise is intended to practice the skills acquired in GIT while developing a typical website, so the Landing Page was divided into two general sections the upper half (Ovidio) and lower half (Keili).

The main theme selected for the website, is the chef of the restaurant El Bohío (Illescas) with a Michelin star and jury of the Spanish edition of MasterChef: Pepe Martinez.

The upper half of the page is composed of a three sections and the navbar:
	- Hero-Carousel
	- Presentation
	- Additional information

Three sections and a footer were created that make up the general lower half section:
	- Recipes
	- Team
	- Subscription

###### Navbar
--------------------------
This simple navbar allows a smooth experience navigating through the webpage. In addition to Pepe's signature as a brand, the navbar has a link that redirects to every section.

###### Hero-Carousel
--------------------------
This carousel is used as a "Hero Image" of the landing page. Currently consisting of three images with a title and camptions, this section would include news and highlighted stories about Pepe and his work, with links to other pages inside the webpage.

###### Presentation
--------------------------
The first section after the Hero-Carousel is a brief presentation of Pepe's life to explain the purpose of the webpage. In order to make the user experience more enjoyable, the text is accompanied with two ornamental images, a vertical one on the left and a background-less one below the text.

In smaller devices, the left image disappears so the text is easier to read.

###### Additional information
--------------------------
This section includes additional information about Pepe and his life and work. On big devices, this section is a nav-tab with buttons as pills, wich alternates the text inside a box bellow. On smaller devices, for a better experience, this section is displayed as an accordion. In both cases, the buttons are decorated with images of food textures.

###### Recipes
--------------------------
The aim is to represent in a friendly and intuitive way the recipes made by Pepe, being separated by tabs according to the type of preparation Traditional, Tasting and Seasonal, in each one will be explained its preparation and the ingredients needed. 
In a first view, the photograph of the dish will appear with the title of the recipe and a brief description of the content (using fake text).

###### Team
--------------------------
The content is separated with another container, using a different color (El Bohío color palette) to differentiate one section from another.
Here we seek to comment on the effort of the team behind the kitchens of El Bohío and that together with Pepe can make the restaurant work, some carousel photographs of their preparations are shown.

###### Subscription
--------------------------
A brief call to action for users to get a voucher to give a tasting as a gift to a special person, and they are invited to get it by leaving their email in the box on the right side.

## Components
Hero-Carousel:
- Carousel

Presentation:
- Container-fluid
- Grid display (Rows and columns)

Additional information:
- Container-fluid
- Grid display (Rows and columns)
- Accordion
A brief call to action for users to get a voucher to give a tasting as a gift to a special person, and they are invited to get it by leaving their email in the box on the right side.

Recipes section:
- Container-fluid and Row
- Nav nav-tab
- Card groups

Equipment section:
- Container-fluid and Row
- Carousel Dark variant

Subscription section:
- Container-fluid and Row
- Form Control 

## Application

1. Run the project using: `$ npx http-server --yes -c-1`.
2. View the final result of the Landing Page.


## Contributions

Comments or reports about the code at https://github.com/OvidioSantoro/exercise-collaborative-html-website

Thank you very much!