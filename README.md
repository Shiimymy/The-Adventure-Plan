# THE ADVENTURE PLAN

The Adventure Plan is my **personal travel blog** website to help people get ideas for their next holidays. The site will target people who love traveling and are looking for tips and recommendations for a travel which combines historical places to visit with places to relax. It will be *useful for people who need help planning holidays, as they could also get into contact for a more personal approach*.

![responsive screen sample](assets/images/responsive-screen.jpg)

Project url : [The Adventure Plan](https://shiimymy.github.io/The-Adventure-Plan/)

## Features

### Existing Features

#### Navigation Bar

The navigation bar can be found on the three pages. It is responsive and include links to the Home page, the Destinations page and the Contact page. This makes it easier to navigate between the pages.
Also, the active page is underlined in the branding color for better navigation understanding.

![Navigation-bar screenshot](assets/images/navigation-bar.jpg)

#### Hero Section

The hero section is the section the user will see first when landing on the page. It includes a personal picture and content, with the first heading fully responsive.
For more visibility, the content has a transparent dark background and is written in white. Then, the first heading has an animation on load taken from a library, and a logo was included to be eye-catching.

![Hero Section screenshot](assets/images/hero-section.jpg)

#### My View Section

My view section exposes what I am looking for when traveling for the website visitors to know what to expect from it : **History and leasure**. 
It includes a picture from a castle of one of my trips, which aligns with the content. When the screen size is reduced, the responsiveness makes the picture on the left go below the content.

![My view section screenshot](assets/images/my-view-section.jpg)

#### About section

The About section gives a list of the main goals of the website to highlight its purpose. The section is divided into two parts : 
- The left has a heading and a small introductory sentence,
- The right is the list of goals with a background picture to keep the user engaged in the reading and make them curious.  
This section is also responsive and the right section on a full screen will go below the section heading on a small screen.

![About section screenshot](assets/images/about-section.jpg)

#### The Footer

The footer can be found at the bottom of all three pages. It includes social media links and a button to invite visitors to the contact page. The users will then choose their preferred method of contact.

![Footer screenshot](assets/images/footer.jpg)

#### Destinations

The destinations page is the second page of the website. It is where the user will be able to see six different destinations at the moment. They will be able to see a picture that illustrates each one of them, along with content that introduces them. 
The content is created to align with the "My view" section on the first page. A button is also included for each destination to check the recommended itinerary *(coming soon)*.

![Destination page screeshot](assets/images/destinations-page.jpg)

#### Contact page

The contact page has a form included for users who would like to have a personnalised travel plan. They can provide the minimum information to get in touch but also an idea of what they are expecting : destination and travel duration.
Once the form is sent, a thank you message will appear to confirm that the form has been sent. The user will be asked to complete all input to be able to send the form. 

![Contact page screenshot](assets/images/contact-page.jpg)

### Features Left to Implement

The next feature will be to create a page for each itinerary button. Each page would have the same structure as the other page : navigation bar, main heading, and footer. 
On each destination page, we would find an itinerary with historical sites to visit, places to relax, and foods to try.

![Check itinenary button screenshot](assets/images/check-buttons.jpg)


## Testing


### Manual Testing 

I checked first and confirmed that the website was working on different browsers : Google Chrome, Microsoft Edge, and Firefox.

Through manual testing, I checked all the links, and I realised that the social media links were not working. I discovered that I forgot the "https://" at the beginning of each url and fixed them afterward.

I manually checked if the responsiveness was working and if it was smooth enough.
For media queries, I made some changes after testing and adapting the css of the contact page and the footer links.

### Validator Testing

 - HTML Testing : 
  Errors found with [W3C Validator](https://validator.w3.org/#validate_by_input) in all buttons as I used an anchor tag as parent element. All button elements were deleted, and I styled the anchor element to look like a button.
  There were also paragraph ending tags on their own, which were deleted.
  
- CSS Testing : 
  No error was found when passing through the official [Jigsaw Validator](https://jigsaw.w3.org/css-validator/).

### Unfix responsiveness

I left for the moment the unresponsiveness of the contact.html page for some tablets due to time, but I will add it in the future.

### Performance Testing

I used [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/) to test the performances of my 4 pages. The results were positive, as scores were between 76 and 90. Please find the result below at the time of the tests : 

- Index page performances : 
![index performance](assets/images/index-performance.jpg)
- destinations page performances : 
![destination performance](assets/images/destinations-performance.jpg)
- contact page performances : 
![contact performance](assets/images/contact-performance.jpg)
- thanks page performances : 
![thanks performance](assets/images/thanks-perfomance.jpg)

## Deployment

- Fork template
The first step before coding was to fork the [ci-full-template](https://github.com/Code-Institute-Org/ci-full-template) from [Code Institute](https://codeinstitute.net/) as asked. To do so, once on the ci-full-template in Github *(as per the first link)*, I clicked on **Fork** on the top-right of the page. Then I renamed the repository with the name of my project under **Repository name** and clicked to **Create Fork**. This allowed me to update the template.

- Project deployment
Once the site was nearly ready, it was deployed thanks to [Github](https://github.com/) from the [The-Adventure-Plan repositorie](https://github.com/Shiimymy/The-Adventure-Plan).
Once in the repository, I clicked on **Settings** in the top navigation bar, then on **Pages** in the left menu. Once the page opened, in the **Branch** section, I chose **main** in the drop down menu and clicked on **Save**.

- Clone project 

This project will be also cloned to work localy on the future realesed by following these setps :
1. Go in [The Adventure Plan repositorie](https://github.com/Shiimymy/The-Adventure-Plan),
2. Click on Code to find the URL and copy it.
3. In the Terminal write *git clone* and paste the url.
4. Press Enter to create the clone.

## Credits

### Content

- The social media icons and the compass icons were taken from [Font Awesome](https://fontawesome.com/).
- The header animation in index.html was taken from [Animate.css](https://animate.style/).
- Instructions on how to implement grid were taken from [MDN](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_grid_layout/Box_alignment_in_grid_layout).
- Instructions on how to implementthe *required* attribute for radio buttons were taken from [Stackoverflow](https://stackoverflow.com/questions/8287779/how-to-use-the-required-attribute-with-a-radio-input-field).
- Website structure inspiration taken from [Love Running project](https://github.com/Code-Institute-Solutions/love-running-2.0-sourcecode). 

### Media

All pictures were taken during my trips, as I want to display my own experiences on this website.