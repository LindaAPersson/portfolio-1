# portfolio-1
# Visit Sweden
The Visit Sweden webpage is for people thinking about taking a trip to Sweden, but want some more information about the country. They can find some general and fun information about the country and some useful information about a few cities. There is also a form that allows users to fill in some personal information that will get them help to plan a customized trip.
![Screenshot of responsive design](assets/readme-img/responsivedesign.png)

## Features
### The header
At the top of the webpage there is a header section with a logo, tagline and a navigationbar/menu underneath. The menu helps the user to navigate to three different sections/pages, home(index), cities and contact-me. 
The logo is partially yellow on a blue background (to symbolize the Swedish flag). 
The navigation is in white on a blue background, in an easy-to-read font. The white color on a blue background creates good contrast and visibility. 
The header section of the page clearly tells the user the name of the page, its purpose and where they can find the information. 
![Screenshot of header](assets/readme-img/header.png)

### Home
The starter page on the webpage (index.html) gives the reader some general information about the country Sweden. The user can also read some “fun/interesting” facts about Sweden, and the purpose of that is to get them more interested in the country.  
![Screenshot of the starter page](assets/readme-img/home.png)

### Cities 
On the cities page the user can see four different cities in Sweden. There is a picture and some short information about the city. The page change layout depending on what screen the user use.   
![Screenshot of the city page, laptop-size](assets/readme-img/cities-laptop.png)
![Screenshot of the city page, tablet-size](assets/readme-img/cities-tablet.png)
![Screenshot of the city page, mobil-size](assets/readme-img/cities-mobil.png)

### Contact me!
The form on the “contact me!” page is created so the user can leave some personal information and get help to book a trip to Sweden in return. 
The form collects the user´s first and last name, the email address, a date for when the user wants to make the trip, and a choice of which city they want to visit. 
![Screenshot of the contact-me page](assets/readme-img/contact-me.png)

### Footer
The footer has a line of text that encourages the user to have a look at the social media of the company. And the logos and links to three different social media platforms. The links open in a new tab. 
![Screenshot of the footer](assets/readme-img/footer.png)

## Testing
### HTML
The link in the logo that takes you back to the home page(index.html) works when tested. 
The three links in the Menu (navbar) work from all three pages. 
The three links to the social media platforms in the footer work and open in new tabs. 
The “contact me” form works when tested. The email area needs to have a proper email address or you can´t submit the form. The submission button works and the drop-down-list shows all four cities. You can´t submit an empty form.   

### UX 
- The site has a good contrast between the background and the text. The yellow parts in the logo have a lower score but since it´s in a big font it still passes. Tested with [Contrast Checker](https://webaim.org/)
- All the pages are responsive, from mobile size to laptop size - 320px to 1920px. Tested with Devtools. 

## Validator 
## HTML
The HTML code was tested with the W3C validator and no errors were found on any of the three pages. 
![Screenshot from W3C validator of the starterpage](assets/readme-img/validate-home.png)
![Screenshot from W3C validator of the cities-page](assets/readme-img/valindate-cities.png)
![Screenshot from W3C validator of the contact-me page](assets/readme-img/validate-contact-me.png)

## CSS
The CSS code was tested with the W3C Jigsaw and no errors were found.
![Screenshot from W3C Jigsaw of the CSS-code](assets/readme-img/validate-css.png)

## Lighthouse
Checking the site through Lighthouse, the site had a bad performance score when it analyzed the mobile version. That is because I don’t have the knowledge I need to manage the images properly.  
![Screenshot from the Lighthouse report on mobil-size](assets/readme-img/Lighthouse-mobil.png)

When checking the site through Lighthouse on a desktop version, the score improved.  
![Screenshot from the Lighthouse report on desktop-size](assets/readme-img/Lighthuse-desktop.png)

### Deployment
This page was deployed through GitHub Pages through these steps:

1. Log into GitHub.
2. Locate the right GitHub Repository.
3. At the top of the repository, select Settings from the menu.
4. Scroll down the Settings page to the "Pages" section.
5. Under "Source" click the drop-down menu labeled "None" and select "Main".
6. When selected, the page will automatically refresh and the website is deployed.
7. Scroll back down to the "Pages" section to get the link to the webpage.

Here´s the link to the deployed site [Visit Sweden](https://lindaapersson.github.io/portfolio-1/index.html)

Unfixed bugs
- There are no unfixed bugs at the deployed site. 

### Bugs and debuging 
- The link in the logo didn’t work. Solution: Moved the link to the right place in the HTML code. 
- The id=yellow was used on two different attributes. Solution: Changed the ID to a class attribute. 
- W3C validator gave an error on the drop-down menu in the form section, because it was missing a first choice  when loading the page. Solution: Created another <option> with a value of none.  

## Further development
If I had more time the next step for the page would be to make individual pages for all the cities. So when the user chooses a city, they can click on it, get directed to a separate page, and get more information and pictures on the city. 
The site could also benefit from a more advanced and detailed form section, so the user can provide more information to the person who is going to organize the trip. 

## Credits
- The code and images for the favicon are from: [Favicon Generator](https://realfavicongenerator.net)
- The code and links for the footer are from: Love Running Project 

## Media 
All background and city images are royalty free from: [Pixabay](https://pixabay.com/sv/)
The symbols are from: https://fontawesome.com

The screenshots are from: 
- [W3C Jigsaw](https://jigsaw.w3.org/css-validator/)
- [W3C validator](https://validator.w3.org/)
- [Am i responsive?](https://ui.dev/amiresponsive)
- [Visit Sweden](https://lindaapersson.github.io/portfolio-1/index.html)
- Lighthouse
