# Flye Website Design Challenge

I have created this website as part of the assignment for an internship. The project displays the home page of the website. I have designed the UI completely from scratch in HTML from the designs provided in Adobe XD([here](https://xd.adobe.com/view/62beadb2-fac2-491b-90d9-5bc90d77ae70-37ed/specs/)). 

The website is hosted using Github pages at [anku07.github.io/fyle-website](https://anku07.github.io/fyle-website/). Please checkout the website.

## Technologies Used:

Since the assignment did not allow use of any frameworks, I have created this website statically using -

1. HTML
2. CSS
3. Bootstrap
4. jQuery

## Features Included:

- The website has a *Contact Us* that is created using `Form` component in HTML. It takes in inputs like **email**, **first name**, **last name** and **checkbox consent** from the user and allows them to send a message to the website owners. The message is sent using jQuery scripting and a tool called [app.getform.io](https://app.getform.io) which is used to host the API for the form and collect the user responses.
- Second feature would be a moving an Carousel. This Carousel contains of cards that can flip and have some content on there back side. Each carousel item contains content on there backside which can be viewed by hovering on the card. The content contains link to [fylehq.com](https://www.fylehq.com/) which opens in a new tab.
- The product also has a modal pop-up view which is used to the Contact Us form view.
- Then there is a section in the product that has an image view and a content view, the interesting thing about this section is that the images changes based on the content that is selected. Which means each item in the content section has an associated image, and this image is displayed when the item is selected. This is done using *jQuery*.

## Project Code Structure

The project contains of three sections -
1. HTML views
2. Assets - icons, images etc
3. CSS files

So the project has

1. **index.html** file - This is the main html file that contains all the HTML code, embedded links, inline CSS, etc.
2. **./assets** directory - This directory contains all the assets used in the project. All the icons and images combined.
3. **./styles** directory - This directory contains `styles.css` file which hosts all the CSS classes used in the product.