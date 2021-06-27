
# Siana's Gallery

This website was produced by myself for Siana Gilbertson, an artist wanting to expand their personal brand and reach. Siana's Gallery was designed based upon Siana's knowledge of the art community that they are a part of and is influenced by websites of other artists (these websites will be credited below)

- [Siana's Gallery](#siana-s-gallery)
- [Design](#design)
    + [Desired Features](#desired-features)
    + [Wireframe Designs](#wireframe-designs)
        + [Homescreen Design](#homescreen-design)
        + [About Page Design](#about-page-design)
        + [Photography Page Design](#photography-page-design)
- [Features](#features)
- [Testing the website](#testing-the-website)
- [Deployment](#deployment)
- [Acknowledgements](#acknowledgements)

## Design
### Desired Features
- Two galleries for showing Siana's Photography and Character Design separately
- Unique 'Splash Screen' style menu as a separate page incorporating Siana's art
- Contact page to allow people to contact Siana for collaboration, commisions and questions
- Footer with icons linking to Siana's social media

### Wireframe Designs
#### Homescreen Design
![Homescreen Design](./assets/images/readme-images/home-screen-design.png "Home Screen Wire Frame")
- The boxes with crosses are images, specifically they are going to be characters designed by Siana. The design for these will be the characters falling from the sky.
- Each character will have text under it annotating what page it links to
- The sky will be the background of the image

#### About Page Design (Previously Contact Page Design circa 22/06/2021)
![About Page Design](./assets/images/readme-images/contact-page-design.png "Contact Page Wire Frame")
- The contact page will have a contact form contained within a box.
- The background of the contact form itself will be a different colour to the rest of the page for contrast
- This design may differ from the finished project, as an alternative to having the icons for separate pages, having one icon to send the user back to the splash screen
- The box with text on the side will be a privacy policy as the user's data would be processed in order for them to contact Siana
- The hamburger button of the mobile view should take the user back to the home page/splash screen
/
##### About Page Design Changes
Due to time limitations, I will not be able to produce a wire frame for this new design. However, the layout will be very similar to the initial design. The about page will incorporate a contact form for the user to contact Siana, but extra information regarding the site owner and a video embedded from Youtube.com will be included. The contact form will be at the bottom of the page, the information regarding Siana at the top. The extra features to be included are as follows, in priority order:
- Information regarding Siana
- Video produced by Siana
- Call to action to fill in the contact form
- Small gallery, taking up one image space and revolving through the different images

#### Photography Page Design
![Photography Page Design](./assets/images/readme-images/photography-page-design.png "Photography Page Wire Frame")
- The photography and character design pages will be organised into four columns
- The pictures will each have a caption underneath it, detailing information regarding the image
- The mobile view will have a 'slideshow' style gallery, where per button click going back and forward the caption and the image will change.

## Features

### Implemented Features


### Future Features

## Testing The Website

This section will be for testing the website.

### Bugs and errors

#### 26/01/2021 - Instagram Embedded Post
- Post functions normally under desktop conditions using a vertical scroll bar to view the whole post
- When in mobile view the Instagram post should go to 100% height so that the whole post can be seen
- When in mobile view, the post cannot be scrolled on and isn't the correct height
- Possible causes:
    + Container is preventing post from being full height
    + Container has overflow: hidden; property
        - Container column-about-right has property `overflow-y: visible;`

### Testing Responsiveness
<table>
<tr>
<td> TOOL/DEVICE </td><td> BROWSER </td><td> OPERATING SYSTEM </td><td>SCREEN SIZE</td><td>RESULT</td>
</tr>
<tr>
<td>REAL: Oppo Find X2 Lite</td><td>Opera Browser</td><td>Android 11</td><td>W1080px X H2400px</td><td>index.html: no issues. photography.html: no issues. characterdesign.html: no issues. about.html: no issues. </td>
</tr>
<tr>
<td>REAL: Honor 20</td><td>Chrome Android</td><td></td><td></td>
</tr>
<tr>
<td>CHROME: Moto G4</td><td>Chrome Developer Tools</td><td></td><td></td>
</tr>
<tr>
<td>CHROME: iPhone 5/SE</td><td>Chrome Developer Tools</td><td></td><td></td>
</tr>
<tr>
<td>CHROME: iPhone 6/7/8</td><td>Chrome Developer Tools</td><td></td><td></td>
</tr>
<tr>
<td>CHROME: iPad</td><td></td><td></td><td></td>
</tr>
</table>
  
### W3.org Validators
#### HTML Validator

The first test using the HTML Validator available through validator.w3.org showed three errors on the index page. See below:

![Index validator HTML 25-06-2021](./assets/images/readme-images/html-validator-index-250621.png "HTML Validator Index")

To fix these three errors I added alt text to the images on the index.html page. For example: `<img src="assets/images/daliah-falling.png" class="nav-img" alt="Photography Page Link">`

Next, I tested the character design page. It showed the following warning:

![Character validator HTML 25-06-2021](./assets/images/readme-images/html-validator-characterdesign-250621.png "HTML Validator character design")

This test came up with a warning that the section I used for semantics had no heading. To fix this, I moved the starting tag of the section to above the header. I checked the photography page for this same error but found that I had not added a section tag. So, I added a section tag around the header of the page and the contents.

When testing the photography page the errors that came up were the same as the index page. No alt text was applied to any of the images present. At this time (25/06/2021 17:00) I have not been supplied any of the images to be put on the website by Siana, so I have used placeholders in the mean time. Until then, I will not know what alt text to add.

Finally, testing the about page using the validator showed the following errors:

![About validator HTML 25-06-2021](./assets/images/readme-images/html-validator-about-250621.png "HTML Validator About")

All of the errors shown bar the warning at the top are from the code provided by Instagram for embedding a post. At this time, I don't believe there is any reason to fix it as it is code provided by Instagram and I do not have the technical knowledge to understand the issues. However, I have fixed the section warning in the same manner that I fixed it on the character design and photography pages. 


## Deployment

This section will be about the deployment of the website to GitPages.

In order to deploy a GitHub Pages site, we must first go to the repository where the desired website is located.

![Github Repository](./assets/images/readme-images/github-repo.png "This Website's GitHub Repository")

This is the repository for this website. The next step is to go to the 'Settings' menu at the top of the page.

![GitHub Settings](./assets/images/readme-images/github-settings.png "Settings for this repository")

Then, we move to 'Pages' near to the bottom of this list on the left.

![GitHub Pages Before](./assets/images/readme-images/github-pages.png "GitHub Pages before deployment")

From this page, we go to 'Source' and select 'Master' from the dropdown list and save. Once we save, it refreshes the page and shows up as shown below.

![GitHub Deployed](./assets/images/readme-images/github-deployment.png "Deployment confirmed in GitHub")

The link in the green box now takes us to the deployed website. From here, I need to check that all of the images are loaded correctly and try the website on multiple browsers on multiple different devices. This is to ensure that the website is functional on as many different platforms and screensizes as possible.

![GitHub Settings](./assets/images/readme-images/deployed-site.png "Deployed Website on Chrome. Screen Size: 1920px*1080px")

The above is a screenshot of the splashscreen "index.html" on my laptop screen. The screensize is 1920px by 1080px. This shows that the images have loaded and that it looks as intended.


## Acknowledgements

- W3Schools.com has provided insight and templates for the website and has been an invaluable tool (see w3schools.com)
- Stack Overflow has helped me troubleshoot issues regarding the HTML and CSS of the website as well as some issues regarding Gitpod that I encountered (See Stackoverflow.com)
- https://css-tricks.com/on-object-fit-and-object-position/ to help with positioning the images in the gallery
- https://www.w3schools.com/css/tryit.asp?filename=tryresponsive_col-s helped with responsivity of the gallery
- FontAwesome allows for the use of icons throughout the website, including the menu icon.
- Wallpaperaccess.com was used for a placeholder image of the sky
- Placeholder images are from placeimg.com
- https://www.markdownguide.org/cheat-sheet/ Helped with producing this document
- https://stackoverflow.com/questions/33661263/footer-pops-up-halfway-up-page/33661595 helped with issues regarding the position of the footer
- https://codepen.io/raubaca/pen/PZzpVe Helped with researching the possibility of a responsive drop down menu under the burger button
- https://www.w3docs.com/snippets/css/how-to-set-the-size-of-a-checkbox-with-html-and-css.html helped with responsivity regarding the checkbox on the about page
- Using Google Fonts for the site's Logo. Specifically the Grand Hotel font.
- https://css-tricks.com/snippets/css/scale-on-hover-with-webkit-transition/ helped with animating the text on the index.html page.

## Content

Content on the page was written by myself (Brandon) and Siana. The privacy policy, temporary image descriptions in the photography page and the text in the about section was my doing. Soon, Siana will create her own content to overwrite these (bar the privacy policy).

## Media

All media on the page was created by Siana except the following:
- Photography page gallery has placeholder images as mentioned in the acknowledgements section. These are from placeimg.com
- The site's temporary favicon (an artist's pallet) is from favicon.io
- Siana created the embedded media. She created the YouTube video in the characterdesign.html page and in about.html. The Instagram post embedded in about.html is also her creation.


  
