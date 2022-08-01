# Minster Tours

[Link to the live site](https://maddiecastle.github.io/minster-tours-project/)

Minster Tours is a site for a company offering tours around York Minster aimed at informing people about the services offered and enticing them to book onto a tour. The site will be useful for people to book a place and discover exactly when and where their tour will start. It will be aimed at tourists searching for activities in York and also at anyone interested in learning about the history of the Minster. 
![Demonstration of Minster Tours on different screen sizes](/assets/images/viewportsizes.jpg)

## Features
- ### Navigation

    - The navigation bar aids the user by providing fast and easy access to the information on different parts of the site.
    
![Navigation bar screenshot](assets/images/Navigation.jpg)

- ### Book a tour button

    - This button draws the users attention because it is in the center of the screen and is a different color.
    -This aids the user by directing them to the booking form.

![Book a tour button screenshot](/assets/images/bookatourbutton.jpg)

- ### Booking form

    - The booking form will allow the user to book onto a tour.
    - This will be the main aim of users coming to the site, and the simple design will allow them to sign up easily.

![Booking form screenshot](/assets/images/bookingform.jpg)

- ### Social media links

    - The links to social media give the user access to other resources to find other people going on the tours and to contact Minster Tours about any questions they have.

![screenshot of social media links](/assets/images/sociallinks.jpg)

## Testing

- I tested different browsers (Firefox, Chrome, and Microsoft Edge) to confirm this page works with all of them.

- I tested that all of the links, both internal and external, work correctly and open a seperate tab when needed.

- I confirmed that the form works, posts correctly, and has character limits where they are needed.

- I confirmed that the readability is not impacted by changing screen sizes, and that the project is responsive accross different devices.

## Bugs

### Solved Bugs

- When first added the external links in the footer where not opening in new tabs, adding
> target="_blank"
to the anchor elements fixed the problem.

- When I first ran my code through the W3C HTML validator, I discovered I had a button element nested inside an anchor element.
- Simply removing the button element and styling the anchor tag like a button fixed the problem.

## Unsolved Bugs
- There are no unsolved bugs.

## Validator Testing
- HTML
    - The official W3C validator returned no errors when passing my code through

- CSS
    - The official Jigsaw validator returned no errors when passing my code through

- Accessability
    - I have confirmed through lighthouse that the site is accesable and easy to read
![Lighthouse test screenshot](/assets/images/lighthousetest.jpg)

## Deployment
- Github pages was used to deploy the site live, via the settings tab of the GitHub repository.
- Then choosing the root option under the Branch subheading.
-This resulted in a live site [here.](https://maddiecastle.github.io/minster-tours-project/)

## Credits
### Contents
- All contents were created by the developer.

### Media
- The landing page background was from Wikimedia Commons [here.](https://commons.wikimedia.org/wiki/File:York_Minster_from_M%26S.JPG)
- The About us section image was from Wikimedia Commons [here.](https://commons.wikimedia.org/wiki/File:York_Minster_nave.jpg)