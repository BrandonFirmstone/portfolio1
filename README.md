# Siana's Gallery

This website was produced by myself for Siana Gilbertson, an artist wanting to expand their personal brand and reach. Siana's Gallery was designed based upon Siana's knowledge of the art community that they are a part of and is influenced by websites of other artists (these websites will be credited below)

![Siana's Gallery Overview Image](./assets/images/readme-images/sianas-gallery-overview.png)

## Table of Contents
  * [Website Purpose](#website-purpose)
  * [Design](#design)
    + [Desired Features](#desired-features)
    + [Wireframe Designs](#wireframe-designs)
  * [Design Choices](#design-choices)
  * [Features](#features)
    + [Implemented Features](#implemented-features)
    + [Future Features](#future-features)
  * [Testing The Website](#testing-the-website)
    + [Known Bugs and errors](#known-bugs-and-errors)
    + [Testing Responsiveness](#testing-responsiveness)
    + [Functionality testing](#functionality-testing)
      - [Form dump screenshot](#form-dump-screenshot)
    + [Chrome Lighthouse Audit](#chrome-lighthouse-report)
    + [End User testing](#end-user-testing)
    + [W3.org Validators](#w3org-validators)
  * [Deployment](#deployment)
  * [Acknowledgements](#acknowledgements)
  * [Content](#content)
  * [Media](#media)

## Website Purpose

The purpose of the website is for Siana to expand her personal brand awareness and to be more visible to potential clients and employers. Due to the nature of Siana's work, this needs to be done through a portfolio-style gallery to show the end user demonstrations of Siana's skills. The website should also appeal to the art community that Siana is a part of.

Website purpose: To expand Siana's personal brand and gain employment/clients 
<br>
Target audience: Employers, artistic community


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
Due to time limitations, I will not be able to produce a wire frame for this new design. However, the layout will be very similar to the initial design. The about page will incorporate a contact form for the user to contact Siana, but extra information regarding the site owner and a **video embedded from Youtube.com will be included.** The contact form will be at the bottom of the page, the information regarding Siana at the top. The extra features to be included are as follows, in priority order:
- Information regarding Siana
- Video produced by Siana
- Call to action to send the user to the contact form
- Small gallery, taking up one image space and revolving through the different images

#### Gallery Pages Design
![Photography Page Design](./assets/images/readme-images/photography-page-design.png "Photography Page Wire Frame")
- The design for the Photography and Character Design pages are identical in terms of layout.
- The photography and character design pages will be organised into four columns
- The pictures will each have a caption underneath it, detailing information regarding the image
- The mobile view will have a 'slideshow' style gallery, where per button click going back and forward the caption and the image will change.

## Design Choices

### Colours
![Colour Pallet](./assets/images/readme-images/colour-scheme.png)
The picture above was taken from coolors.co. 
- The colour pallet was chosen by myself and Siana after researching different potential pallets and colour schemes.
- The primarily orange and blue colour scheme was chosen as I believe it invokes a positive experience from the user
- Both colours I believe suit the website. Siana's art is very vibrant and bold in colour. 
- According to [this document](https://www.verywellmind.com/the-color-psychology-of-blue-2795815), the colour blue invokes "feelings of calmness or serenity. It is often described as peaceful, tranquil, secure, and orderly."
- From [this document](https://www.verywellmind.com/the-color-psychology-of-orange-2795818#:~:text=Orange%20calls%20to%20mind%20feelings,in%20traffic%20signs%20and%20advertising.), the colour orange causes feelings of excitement, enthusiasm, and warmth", feelings I believe benefit the website
- The above document also mentions the following: "Orange is often used to draw attention, such as in traffic signs and advertising." - why it is used in the header and footer sections.



### Typography

- The majority of the page is in the font family Arial, Helvetica, sans-serif; 
- This is a very standard font selection as it is highly accessible and easy to read due to it's sans-serif nature.
- The font that Siana chose for her logo is a [Google Fonts](fonts.google.com) font called Grand Hotel, with Helvetica and sans-serif as the backup fonts
- Siana chose this font because she believed that it suited the artistic nature of herself and the website. 
- It's not perfectly easy to read but it is still very easy to read in itself because each letter is quite distinctive in the font

### Images

- All of the images bar the background image for index.html were created by Siana
- The purpose of these images is to demonstrate Siana's skills and the variety of them
- While not all of the images are currently on the website, primarily in photography.html, every image will be unique in itself in order to show Siana's abilities
- The cloud background was found on wallpaperaccess.com and is copyright free.
- The only images with functionality and website-specific purpose are the index.html navigational images
- The idea behind these images was that the characters will be falling out of the sky and that each one would be a functional link to a page
- This is a fun and quirky approach to a navigational page/splash screen and I believe that users will be intrigued by the unusual choice

### Animations and Transitions

- The main animations are on the navigational links on the website
- On the splash screen page, each text label scales to 1.1 and changes to white on hover. 
- This is to ensure that the user is aware that this is a clickable link
- The logo on each page bar the index page also has this feature, in order for the user to know that it can be clicked to take them back to the splash screen.
- An animation is used for opening the navigational menu with the burger button (of which changes colour to white on hover)
- The menu opens up in two seconds, revealing the links to each page.
- I believe this feature keeps the website more in-tune with modern websites.
- A navigation menu that opens up instantaneously doesn't feel to have the same polish as one that opens up slowly.
- Each list item in the navigational menu transforms from a white background to a faint orange one and the text changes to grey.


## Features
### Implemented Features
The below are features that have been incorporated into the website.

#### Index page

![Index Page All Devices](./assets/images/readme-images/index.html-all-devices.png)

- The index page has been designed to highlight Siana's creativity.
- The actual index.html page is a splash screen navigation page.
- The page features three of Siana's main character designs falling through the sky.
- Each image can be clicked on to take you to the respective page and when hovering over the labels underneath the text scales in size and changes colour to white. This is to better show that they are clickable links. 
- Siana did not want the page to include a footer, as the main focus should be the navigational links and the character art itself. However, temporarily to fix a responsivity issue detailed in the testing section, I've added a footer with Siana's agreement that it's more important for it to be responsive for the time being.
- The page has a navigation bar and a footer containing icons.

#### Character Page Design

![Character Design Page All Devices](./assets/images/readme-images/characterdesign.html-all-devices.png)

- The character page includes two rows of four images.
- Each image has a brief description underneath.
- The page title is included on the top as well as a small caption.
- Underneath all of the gallery images is an **embedded YouTube video** of Siana going through one of her sketch books.
- When the device size reduces to that of a tablet or similar, the images are then displayed in rows of two
- When reduced to mobile, a single image is shown in a row
- The page has a navigation bar and a footer containing icons.

#### Photography page
![Photography Page](./assets/images/readme-images/photography.html-all-devices.png)

- The photography page in terms of format is identical to that of the character design page.
- The page has two rows of 4 images on desktop, 2 items per row on tablets and 1 item per row for phones.
- The site has none of Siana's photographs as she has not currently provided them
- The placeholder images are from **https://placeimg.com/600/600/any**
- The page has a navigation bar and a footer containing icons.

#### About page

![About Page top](./assets/images/readme-images/about.html-top-all-devices.png)

- The top of the about page details information about Siana and her interests. 
- This page is used to tell the user a brief summary of what she does and the fact that she is open to work and also provides a means of contact. 
- A **YouTube video and Instagram post is embedded** to link to her two main social channels to gain brand awareness - one of the main goals of the website.
- The content in the about section was written by myself as a temporary placeholder for the content Siana wants to write.
- The about includes a call-to-action style link to the contact section at the bottom of the page.
- The page has a navigation bar and a footer containing icons.

![About Page Contact Form](./assets/images/readme-images/about.html-contact-all-devices.png)

This is the contact form used to get in touch with Siana. It contains four main fields:
- The full name in order for the user to tell Siana their name. The user does not have to fill this out as in the artist community people do not normally use their real names. 29/06/2021 - Siana has requested that this field be required so that she can address the user more easily. She also requested that it be changed to "Name/Username" so that it can apply to employers and other members of the art community.
- The e-mail address is used for Siana to contact the user and is a required field - there's no point in the user filling out the form if Siana can't respond to them.
- The enquiry section uses a text area so that the user can type out whatever enquiry they would like. This isn't required as simply with their e-mail address Siana could contact them and ask what they contacted for. 29/06/2021 - Siana has asked for this to be required so that she can more easily respond to users. Added required to element.
- The consent checkbox is a required field with the attached label telling the user to read the privacy policy. The privacy policy, writted by myself, in a nutshell tells the user that their information will only be used to contact them and will not be saved longer than necessary. If this was not a required field there would be no point in the user filling out the form as they wouldn't be consenting to being contacted. 
<br><br>
The about page has changed considerably since the wireframe drawings. Originally just a contact page, the about page has evolved into a more practical being. The about section should help to draw the user into contacting Siana by telling them that she is open for work and any enquiries. There is also a link to the contact form in the about section acting as a text-based call to action.

#### 404 page

![404 Page All Devices](./assets/images/readme-images/404.html-all-devices.png)

- The 404 page shows when the user goes to an incorrect URL.
- It includes the burger button to help the user navigate to where they need to be.
- The layout of the page is identical to the rest of the website, making it consistent in style, layout and in terms of navigation
- The content on the page also includes another link to the index page.
- The page has a navigation bar and a footer containing icons.

#### Header
![Navigation Screenshot](./assets/images/readme-images/navigation-screenshot.png)
- The navigation bar is used to enable the user to easily navigate between pages
- The list of pages is only opened when the user clicks the burger button on the top right
- When you hover over the burger button it changes colour to white
- On the left is Siana's logo, using an imported Google Font
- When hovering the cursor over the logo, it transforms to a scale of 1.1 in an animation of 2 seconds in duration
- When clicking on the logo, it takes you to index.html


#### Footer
![Footer Screenshot](./assets/images/readme-images/footer-screenshot.png)

- The footer is used to link the user to Siana's different social media channels
- This is to help Siana achieve her website's end goal - expand her personal brand
- Each icon rotates by 30 degrees left and right alternatively.
- Each link opens into a new tab on the browser to ensure the user retains Siana's website
- Currently, only Youtube and Instagram icons take you to Siana's accounts/pages. This is because Siana plans on but hasn't currently created accounts for Twitter or Facebook.

### Future Features

#### Index page
- No footer at the bottom of the page
- Animated characters on hover
- Caption under Siana's Gallery title
- Animation when transitioning to a different page

#### Character Design Page
- Case Studies under gallery to show what people have commisioned or what Siana has done in employment
- Sliding/revolution gallery on mobile view
- Image doesn't open to new tab - appears large in middle of page with x button in corner to close

#### Photography page
- Siana needs to transfer photographs to me in order for me to upload them
- Videos embedded in page such as nature vidoes, blogs, any freelance photography Siana has done.
- Call to action to go to contact page

#### About page
- Content provided by Siana for the contact page
- Contact information so that users can contact Siana themselves (IE a business telephone number and e-mail address.)
- Blog-style about me video done in an artistic manner (for example, see https://en.wikipedia.org/wiki/Draw_My_Life)

#### Store page
- A page with e-commerce features built in
- Used for purchasing prints and other artistic creations by Siana.

## Testing The Website

This section will be for testing the website and ensuring that functionality and responsivity work as expected.

### Known Bugs and errors

#### 26/06/2021 - Instagram Embedded Post (FIXED)
- Post functions normally under desktop conditions using a vertical scroll bar to view the whole post
- When in mobile view the Instagram post should go to 100% height so that the whole post can be seen
- When in mobile view, the post cannot be scrolled on and isn't the correct height
- Possible causes:
    + Container is preventing post from being full height
    + Container has overflow: hidden; property
        - Container column-about-right has property `overflow-y: visible;`
- To fix the issue, I've used https://codepen.io/rexkirby/pen/LyFzB to fix the embedded post.

#### 28/06/2021 - Gap on Chrome Mobile (TEMP FIXED)
- No functionality is affected. When on Chrome on a mobile Android device, when you scroll down the top bar with the URL and tabs hides. This causes a gap on the bottom of the index page in the background image.
- To attempt to fix this I increased the html height to 120%.
- While the gap in the background is now hidden, the top bar on Chrome still causes a gap on the bottom and depending on how the user scrolls it can hide the 'about' caption on the bottom image. When scrolling, the bottom of the page appears to be above the text, but if you scroll again it shows the text. This is very non-intuitive for the user.
- This issue also appears through the Chrome Dev Tools
- To attempt to fix this, I will add a thin invisible div to the index page, so that hopefully that will be the hidden part of the page. Added the below to responsive CSS:
- ` .index-footer{ width: 100%; height: 80px; display: block;} `
- The above did not work. Unfortunately, to resolve this issue I've added the standard footer to the page. This has resolved the issue.

#### 28/06/21 - Using tab to navigate cycles through the navigation links despite them being hidden (KNOWN - UNFIXED)
- When using the tab key to navigate the page, the navigation links (accessed using the burger button) are selected despite not being visible to the user.

#### 28/06/2021 - Footer appears half way up 404.html page (FIXED)
- When you attempt to access a page that isn't actually a part of the website, the 404 page should be thrown up.
- When accessing the 404.html page through typing in an incorrect URL, the footer is half way up the page.
- To see how I could go about fixing this, I have temporarily added in-line CSS. ` style="position:fixed;bottom:0;"`
- As the 404 page does not work through Gitpod, I will have to push the code to Github and wait for Github Pages to update itself to see.
- This inline CSS has fixed the issue.

#### 28/06/2021 - Gallery images are too large (FIXED)
- When loading up the website, the images take some time to load.
- This is because the images have not been compressed at all.
- In order to fix this, I have used tinypng.com to quickly reduce the file size of these images.
- When loading the characterdesign.html page after emptying the cache, it loads considerably faster.

#### 30/06/2021 - Footer on index page covering labels for each image on certain screen sizes (FIXED)
- On my personal laptop loading up the website, I noticed that the footer was covering the bottom text under each image on the index page. 
- Looking at Chrome developer tools, this only happens on extremely short screens
- To temporarily fix this, I increased the margin-bottom on #nav-wrapper in order to make the scroll bar appear so that the user can scroll to see the text.
- I know that this is not user friendly, but due to time contraints and the fact it happens on very few screen sizes this is an issue that may have to be fixed fully at a later date.
- When trying to repeat the issue on the deployed site, the issue does not exist. I left enough time to ensure that Github pages had updated to make sure that the problem was fixed. 

#### 30/06/2021 - Burger button on very small mobiles not visible (FIXED)
- When using ami.responsivedesign.is the burger button is not visible on the small phone displayed.
- Luckily, I had already made it so that the logo could be clicked to take the user to index.html
- This is not perfect, and in the future it'd be nice to have the logo move to two lines so that the burger button can still be displayed but in the mean time the user is still able to navigate the website successfully.

#### 30/06/2021 - Chrome Developer Tools Errors (UNFIXED)
- When on Chrome Developer tools, the following errors are shown on the about page and the character design page:
![Chrome Errors](./assets/images/readme-images/chrome-errors.png)
- I believe that these are caused by third party websites/embedded code.
- As these errors seem to have no effect on the functionality of the website and time constraints, I have left these alone.
- For future development, I would like to address these to see if there is any possibility of fixing these errors or if they are purely caused by the third party websites.

### Testing Responsiveness
The below table details testing of the responsiveness of the site as well as functionality on different browsers. 
<table>
<tr>
<td><STRONG> TOOL/DEVICE </STRONG</td><td><STRONG> BROWSER </STRONG></td><td><STRONG> OPERATING SYSTEM </STRONG></td><td><STRONG>SCREEN SIZE</STRONG></td><td><STRONG>RESULT</STRONG></td>
</tr>
<tr>
<td>REAL: Oppo Find X2 Lite</td><td>Opera Browser</td><td>Android 11</td><td>W1080px X H2400px</td><td>index.html: no issues. photography.html: no issues. characterdesign.html: no issues. about.html: no issues. </td>
</tr>
<tr>
<td>REAL: Honor 20</td><td>Chrome</td><td>Android 11</td><td>W1080px x H2340px</td><td>index.html: Noticed that on the index page there is a blank space when scrolling down due to Chrome hiding the url bar at the top. No other issues</td>
</tr>
<tr>
<td>CHROME: Moto G4</td><td>Chrome Developer Tools</td><td>Windows 10</td><td>W360px x H640px</td><td>No issues found</td>
</tr>
<tr>
<td>CHROME: iPhone 5/SE</td><td>Chrome Developer Tools</td><td>Windows 10</td><td>W320px x H568px</td><td>No issues found</td>
</tr>
<tr>
<td>CHROME: iPhone 6/7/8</td><td>Chrome Developer Tools</td><td>Windows 10</td><td>W375px x H667px</td><td>No issues found</td>
</tr>
<tr>
<td>CHROME: iPad</td><td>Chrome Dev Tools</td><td>Windows 10</td><td>W768px x H1024px</td><td>No issues found</td>
</tr>
<tr>
<td>Thin laptop</td>
<td>Internet Explorer 11</td>
<td>Windows 10</td>
<td>W1920px x H1080px</td>
<td>Site logo pushes down images, hiding text a little bit under footer - decreased padding to compensate</td>
</tr>
<tr>
<td>Thin laptop</td>
<td>Microsoft Edge</td>
<td>Windows 10</td>
<td>W1920px x H1080px</td>
<td>No issues found</td>
</tr>
</table>
<br>

### Functionality testing
<table>
<tr>
<td><strong> Test </strong></td>
<td><strong> Page </strong></td>
<td><strong> Result </strong></td>
</tr>
<tr>
<td>Do the navigation links take the user to the right place?</td>
<td>index.html</td>
<td>Each link takes you to the correct page</td>
</tr>
<tr>
<td>Are the text links animated correctly?</td>
<td>about.html, characterdesign.html, photography.html (logo), caption text on each image (index.html) </td> 
<td>All text grows in size in a transition and changes colour to white (whitesmoke)</td>
</tr>
<tr>
<td>Do the links in the navigation drop down work correctly?</td>
<td>about.html, characterdesign.html, photography.html</td>
<td>The links take you to the correct pages</td>
</tr>
<td>Do all of the images open in a new tab?</td>
<td>characterdesign.html</td>
<td>Images spindle-sketch.jpg and face-in-acrylic.png throw up error 404. Corrected links to fix this.</td>
</tr>
<tr>
<td>Does the text link to the contact form work as intended?</td>
<td>about.html</td>
<td>The link takes you to the contact form</td>
</tr>
<tr>
<td>Does the contact form prevent you from submitting the form without filling required fields?</td>
<td>about.html</td>
<td>The form cannot be submitted without being filled out correctly.</td>
</tr>
<tr>
<td>Does the form submit to Code Institute form dump correctly?</td>
<td>about.html</td>
<td>The form is submitted to the Code Institute form dump correctly. (see Form dump screenshot belpw)</td>
</tr>
<tr>
<td>Do the footer links take you to the right places?</td>
<td>index.html, about.html, characterdesign.html, photography.html</td>
<td>The Instagram and YouTube icons take you to Siana's pages correctly. The other two do not work as Siana hasn't made accounts for them yet. (but is planning on creating them)</td>
</tr>
<tr>
<td>Does the website flow correctly when navigating using the Tab key? (for accessibility)</td>
<td>index.html, about.html, characterdesign.html, photography.html</td>
<td>The tab key cycles through the navigation links despite them being hidden on all pages. The rest of the page works as expected.</td>
</tr>
</table>

#### Form dump screenshot
![Form Dump Screenshot](./assets/images/readme-images/form-dump.png)

### Chrome Lighthouse Report
- Upon running the Chrome Developer tool Lighthouse on the website, initially it came up with some issues:
  + The pages were lacking in meta descriptions and keywords 
  + Every image on the photography page was lacking and alt tag and title
  + The navigation button did not have an aria-label
  + Every input label on the contact form needs an aria-label
  + The Instagram post was lacking a title

After making changes to the above issues, these were the results that each page received: <br>
**About Page**
![Lighthouse Results for About Page](./assets/images/readme-images/lighthouse-about.png)
- The goal for myself was to ensure that each result was above 85 to ensure that the website is to as high a standard as possible.
- Each result is in the green and best practices is 100
- SEO is high which is good as SEO allows for more people to find the website online

**Character Design Page**
![Lighthouse Results for Character Design Page](./assets/images/readme-images/lighthouse-characterdesign.png)
- The performance is very low for this page.
- This is partly because of the size of the images shown.
- In future, it might be an idea to reduce quality down a bit more to improve speed

**Photography Page**
![Lighthouse Results for Photography Page](./assets/images/readme-images/lighthouse-photography.png)
- The performance on the photography page is higher than the character design page as the images it is loading are of lower quality
- The SEO has been affected as the a tags do not lead to anywhere meaningful at the moment. This will be changed once I have images from Siana to open in another tab

**Index Page**
![Lighthouse Results for Index Page](./assets/images/readme-images/lighthouse-index.png)
- Every score is in the green and above 95
- Nothing needs to be touched with this page

### End User testing
In order to see how a user would react to the website and use the website, I found a volunteer to use the website and try to find any issues or bugs with it. My volunteer is a man named Harry, aged 31. From using the site, the only issue raised is that the page titles were uneven. There was a gap on the left, but not on the right. To fix this, I added `padding-right: 50px;` to .page-title in the css file. This makes for a more aesthetically pleasing experience for the end user.

### W3.org Validators 
<br>

#### HTML Validator
<br>
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

#### CSS Validator

I have tested the site using jigsaw.w3.org's css validator. The website passed the validator's tests as you can see in this link:
https://bit.ly/sianas-gallery-css-validator

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
- Used https://ecotrust-canada.github.io/markdown-toc/ to generate a table of contents
- Used this Codepen to fix Instagram embedded post issues. https://codepen.io/rexkirby/pen/LyFzB
- The below sites influenced the development of the website as they're all artists with similar goals to Siana:
    + https://www.wix.com/blog/2020/09/art-portfolio-website-examples/?utm_source=google&utm_medium=cpc&utm_campaign=9852964004^119455633872&experiment_id=^b^504214426013^^_DSA&gclid=Cj0KCQjw5uWGBhCTARIsAL70sLJVZzGc-ofGIt-a1bLLWSY_s8qHjUVtGzA5I2xSpvYpByMEDysdnrgaAl-OEALw_wcB
    + https://www.pixpa.com/blog/artist-portfolio-websites
    + https://www.format.com/customers/art
- Smooth scrolling found at https://www.w3schools.com/howto/howto_css_smooth_scroll.asp#section2 
- http://ami.responsivedesign.is/# used to take pictures of each page on different devices.

## Content

Content on the page was written by myself (Brandon) and Siana. The privacy policy, temporary image descriptions in the photography page and the text in the about section was my doing. Soon, Siana will create her own content to overwrite these (bar the privacy policy).

## Media

All media on the page was created by Siana except the following:
- Photography page gallery has placeholder images as mentioned in the acknowledgements section. These are from placeimg.com
- The site's temporary favicon (an artist's pallet) is from favicon.io
- Siana created the embedded media. She created the YouTube video in the characterdesign.html page and in about.html. The Instagram post embedded in about.html is also her creation.


  
