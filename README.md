# Visit Glasgow

Visit Glasgow is a site which has been designed to inform foreign tourists, natives and the general public on events being hosted in the city of Glasgow. This also includes details on the main tourist attractions the city has to offer which attracts visitors from all over the globe. This site is particularly useful as it provides direct links to the various events & tourist attractive but ultimately gives you a vibe on how exiting the city is.

![Responsive Mockup](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/mockup-home.PNG)

## Features

### Home Page

**Navigation Bar**

- Featured on all 4 pages, the full responsive navigation bar includes links to Home, What's on, Explore and finally social pages Letter Explore page section. This is identical in each page to allow for easy navigation.
- This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.
- Additionally the nav bar is on a fixed position so the user does not need to scroll back to the top of the page if they wish to change page. This fixture also collapses into a hamburger icon when the screen width is reduced to mobile screen size.
- The particular bold colour which been chosen compliments the famous people make Glasgow image below the navigation bar.

  ![Nav-Open](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/nav-full.PNG)
  ![Nav-Closed](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/nav-closed.PNG)

**Home-Background-Image**

- This section includes a photograph of the iconic People make Glasgow building which in centred in the middle of the city.
- This image is very eye catching and speaks the true values of the city and its people.

![Home-Background](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/home-background.PNG)

### Whats-On-Section

- This section is an area which will inform the user all of the fun/interesting events that are happening in the city right now. This ranges from drinks festivals, music festivals, mini golf, art, food festival. This section covers various types of events which is attractive to types of people.
- Each events provides a thumb nail photo and also a link is provided on the event its self so this will take the user to a direct site of that event if they wish to book tickets.

![Whats-on](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/whats-on-mockup.PNG)

### Explore Page

**Explore-Background-Image**

- The background image for this section features the famous floating heads in the Kelvingrove Art Museum. This is also captured with a text box encouraging visitors to look further into what tourist attractions the city has to offer.

![Explore-Background](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/background-2-mockup.PNG)

**Explore-Tourist-Info**

- This section has been created to inform the user of the various tours, museums, historic Glasgow university tours available.
- This is focused more on the conventional tourist who is keen to explore the historical aspects of the city which applies to a different audience so felt this should be on a separate page.
- Each section ie bus tour, Kelvingrove art museum, Glasgow University has an accompanying image with some brief back-ground text to inform the user of what to expect. The headings also contain links if the user wishes to book tickets.

![Explore-tourist-info](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/get-exploring-mockup.PNG)

### The Footer

- The footer section includes links to the relevant social media sites for Visit Glasgow. The links will open to a new tab to allow easy navigation for the user. This also contains contact info ie email, address & telephone number if a user wishes to get in direct contact with the site.
- The footer finally includes a news letter sign up button which leads the user onto the news-letter sign up page.

- The footer can be viewed in the home, explore, news-letter page. This can also be accessed via the nav bar

![Footer-image](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/footer-mockp.PNG)

### News Letter Page

**Newsletter Background**

- This includes a photo of the famous Buchanan Street which full of designer high-end designer stores which can be seen packed with shoppers

![Buchanan-Street](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/Buchanan-street.PNG)

- This section allows the user to sign up to the weekly newsletter offered. The fields required are first name, surname, email address with an accompanying submit button.
- This features a basic sign up form highlighted in the same colour as the footer. This sign up form is not fully functional as backend technologies will be required which are outside the scope of this project.

![Sign-up](https://github.com/CharlesB91/visit-glasgow/blob/master/assets/images/mock-ups/sign-up.PNG)

## Features Left to Implement

- Additional future features which will improve the sites capability would be to add an interactive map of the full city highlighting historical buildings, museums, popular venues.
- Additionally adding a section with food/drink venues within a carousel would enhance the site also.
- Lastly backend technology’s would make the newsletter sign up page fully functional.

## Testing

### Responsive Testing

- This page has been through extensive testing through google chrome developer tools so that any user using desktop, tablet, mobile device will have a great experience seeing all the visual and text content but also easily navigate through the site.
- Additionally site has also been tested on (https://responsivedesignchecker.com/) for responsive behaviours

### Validator Testing

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcharlesb91.github.io%2Fvisit-glasgow%2F)
  - This was 1 warning and this is due to the home background section being empty as there is no text needed and background image is loaded via css file
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](http://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fcharlesb91.github.io%2Fvisit-glasgow%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)

### Accessibility Testing

- Google Lighthouse returned a report of 98 for accessibility (https://googlechrome.github.io/lighthouse/viewer/?psiurl=https%3A%2F%2Fcharlesb91.github.io%2Fvisit-glasgow%2F&strategy=mobile&category=performance&category=accessibility&category=best-practices&category=seo&category=pwa&utm_source=lh-chrome-ext)

### User Experience Testing

- Asked family members to review my website on various devices on how they found the site. This included how well they navigated if they understood the general idea and concepts. Did receive positive feedback however it was pointed out that the links I have on the images would be better suited to the headings under the images. Have now made those changes.

### Browser Testing

- This site has been testing through various popular browsers for compatibility. These include, Chrome, Firefox, Edge, Safari.

## Bugs

### Resolved Bugs

- Did encounter some bugs whilst building the site in particular the explore page when laying out images on either side of page when viewed on larger screens. Flex box would not allow me to display each image on either side easily with the text underneath of the image ie Glasgow bus tours. After some research via w3 schools it was clear that I had to wrap the image and heading in a separate div from the paragraphs. This then allowed me to position the images the way I wanted.
- Nav bar did have some bugs when screen size was reduced - all nav items could not be seen. This was resolved by reducing the font size via media query.

### Un-resolved Bugs

- No un-resolved bugs.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows:
  - In the GitHub repository, navigate to the Settings tab
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - https://charlesb91.github.io/visit-glasgow/

## Credits

- There has been various sources of credit used for this site.
- Font choice was taking from google fonts (https://fonts.google.com/). There was two main fonts used in the site for heads and paragraphs which have effective contrasting features - "Montserrat", sans-serif;, "Zen Tokyo Zoo", cursive;
- There was 3 main colour choices taken from (https://colorhunt.co/) which helped outline the nav bar, footer and sign up page and finally text. #bf1363; #fb9300; #3a3a3a
- For the responsive hamburger nav bar. Originally the nav bar was responsive however the list options did not transform into the current hamburger nav bar. I sourced code from the following code pen example (https://codepen.io/mutedblues/pen/MmPNPG)
- For the above example the source code, this has to be styled accordingly to how site was to be displayed with font, background colour.
- For the what’s on section & explore which includes images of the various events, attractions i used (https://www.w3schools.com/css/css3_flexbox_responsive.asp) to help guide me on the best way to lay out the images in a responsive mode.
- The footer social icons for facebook, instagram, twitter were used from (https://fontawesome.com/)

## Content

- Text used in the explore section was taken from various sources -
- Glasgow University - (https://en.wikipedia.org/wiki/University_of_Glasgow)
- Kelvingrove Art Museum - https://en.wikipedia.org/wiki/Kelvingrove_Art_Gallery_and_Museum
- Glasgow Sightseeing - (https://peoplemakeglasgow.com/things-to-do/tours)

## Media

- Images in the background image for the home, explore & sign up page were sourced from (https://unsplash.com/)
- Images used in the what’s on section & explore tourist info section were sourced from (https://www.whatsonglasgow.co.uk/)
- Background images had to be resized using (https://promo.com/tools/image-resizer/)
