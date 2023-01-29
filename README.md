# The Bee People
My first Portfolio Project is a site for a fictional wildlife association who’s goal is to educate people about the importance of bees to the eco system, while raising awareness of the issues that bee species face. The target audience for the site is primarily young people and anyone who is seeking information regarding the enviroment, it is visually appealing and provides information in simple terms so as to be accessible to people of all ages and backgrounds.

[Please view the live project here!](https://blahblahblah589.github.io/portfolio-project-1/)

![Am I responsive screenshot](/assets/images/am-i-responsive.jpeg)

## User Experience (UX)
### User Stories
----------------------------
#### First Time Visitor Goals
- As a first time visitor, I want to easily be able to perceive the purpose of the site.
- As a first time visitor, I want to easily be able to navigate the site.
- As a first time visitor, I want to have a positive emotional reaction to the site design.
- As a first time visitor, I want to be able navigate the site intuitively.
- As a first time visitor, I want all of the above to be true, regardless of screen size.
#### Returning Visitor Goals
- As a returning visitor, I want to easily find the page or section that I am looking for.
- As a returning visitor, I want to be able to access the additional reading links with ease.
#### Frequent Visitor Goals
- As a frequent visitor, I want to easily be able to sign up to the site's newsletter. 

### Features
----------------------------
#### Existing Features
##### Header
- The header element is identical across all pages of the site. 
- It contains a heading element that acts as the site title and an anchor back to the homepage, index.html. This is on the right hand side of the header.
- It also contains a navigation menu to all three pages of the site with the current page the user is on underlined. This is on the left hand side of the header, at smaller screen sizes the navigation menu is underneath the h1 element.
#### Splash Page
- Taking inspiration from comic books, the typical hero image has been replaced with a splash page. Three distinct images that match the theme and color scheme of the site, in an inline block formation. 
- At smaller screen sizes the block formation is completed by an animation of bee carrying honey. Each image contains an anchor and a question that will be answered by clicking on it. 
- The first two links are to distinct sections on index.html and thus act as internal page navigation. The third link is to the site's sign up page. Each link asks a question to the user and acts as a call to action.
#### "Why we need to protect the bees!" Section
- This section's purpose in index.html is to educate the reader on the many different ways that bees can benefit the human population. 
- This section is included to engage the reader, to let them know that this issue is relevant to them.
#### "All about the honey!" Section
- This section's purpose in index.html is to educate the reader on the health benefits of honey. 
- The section is included to illustrate to the reader that the cause being promoted on this site can have direct, real world benefits to their health, if they so choose.
#### Table
- The table element included here shows the basic nutritional information of typical honey, compared to the sweetener alternatives. 
- This section is included to further illustrate to the user how helping the honey bee can have a positive direct effect on their health and well-being.
#### Video 
- The video element included in science.html is a easily digestible, 6 minute YouTube video from the channel Kurzgesagt. It was chosen due to it's accessibility, using lay language and colorful imagery the video explains how one of the pillars of human civilisation is the honey bee, and details the issues that the species is facing. Furthering the goal of the site.
#### External Navigation
- A list of external links that will open, in a new tab, pages of prominent wildlife organisations displaying facts about bees. Providing further educational resources to the user about this issue.
#### Form
- The form element on sign-up.html consists of a button and three input elements. One for first name, one for last name, and one for email.
#### Footer
- The footer element is identical across all pages of the site.
- It contains a list element containing anchors to various social media accounts (Twitter, Instagram, Facebook).
- Each link is presented as a FontAwesome icon of each social media company.
#### Features to be added
- In the future I would like to add an interactive quiz to further engage users.
## Design
### Layout
----------------------------
- The header and footer elements are identical on each page of the site, consisting of the site title on the left hand side, and site navigation on the right. The font Nanum Myeongjo was chosen for it's light, yet professional look.

![Header element](/assets/images/header.jpeg)
![Footer element](/assets/images/footer.jpeg)
- index.html consists of three distinct sections, reflecting the rule of thirds. The first third is image based, while also acting as a navigation system for the page itself. The images are inline on large screens and stack as the viewport decreases.  The font for the call to action questions is Pacifico, which was chosen due to its compatibility with the main body font Nanum Myeongjo. And for the relaxed design to add levity to the page, relefting the positive message of the site.

![Splash element](/assets/images/splash-image.jpeg)
- The second third is text based and sticks to the left side on medium sized screens, while becoming central on larger and smaller sized screens. The section consists of a list containing headers and paragraphs.

![Section 2](/assets/images/section2.jpeg)
- The third third is text based and includes a table element. It sticks to the right side on medium sized screens, while becoming central on larger and smaller sized screens. On medium screens an animation plays in the empty space to the left of this section, while disappearing when the section becomes central.

![Section3](/assets/images/section3.jpeg)
- science.html also consists of three sections. One large section containing the video element and two smaller elements above and below.
Above the video element container is a page heading and message for the reader explaining the purpose and contents of the page.

![Science.html header](/assets/images/science.html-aside.jpeg)
- Below the video element container is an external navigation section, providing links to other resources to further educate the user, as per the aim of the site.

![Science.html external navigation](/assets/images/external-links.jpeg)
- The central section of science.html consists of a video element within a container. The video is an external resource from YouTube, explaining the importance of bees to human civilisation. The video will not autoplay and the user has complete control over the video.

![Science.html video element](/assets/images/video.jpeg)
- sign-up.html consists of a page header followed by a form to sign up for The Bee People's newsletter.
Within the form container a thank you message and appeal to the users sits at the top left. The form element occupies the space below and to the right.

![Form element](/assets/images/form-section.jpeg)
### Color Scheme
----------------------------
The final color scheme went through several stages of development. Initially yellow text and element borders was to be set against a black background. However this was found to be too dark and not in keeping with the naturalistic theme of the site. Instead, the current rich and dark gold text is set against a white background. In keeping with the theme of bees and the images that would be used for the site, I wanted to use the colors yellow and black for the text. 
The color #9E6E18 was chosen to make the text stand out more against the white background, over yellow. The text in the splash section is #2F2B11 which was chosen over black; as black was deemed to contrast too much with the bright images in this section. The footer is set to the warm golden color of #dfa640 with black FontAwesome icons, to reflect the color scheme most associated with the bee.
### Media
----------------------------
As well as the media presented in the layout section of this document, additional animations have been included for certain screen sizes.
- On a medium size screen the user will see an animation of a bee flying in a figure eight pattern to the left of Section 3 in index.html.

![Bee gif](/assets/images/bee-gif.jpeg)
- When the viewport is reduced down to the size of a tablet or mobile device an additional animation of a bee carrying honey is introduced alongside the splash images in index.html in order to complete the 2x2 grid format of the splash section.

![Bee gif 2](/assets/images/bee-gif-index.jpeg)
## Testing
### Browser Testing
----------------------------
- I have tested that this site works on macOS (Ventura 13.1).
- I have tested that this site works on Chrome, Safari, and Brave browsers.
- I have tested that this site works and responds to a mobile devise (iPhone 13 Pro).
- All external links open in a new tab.
- The video element does not autoplay.
- The form element validates the input successfully. 
- The site is fully responsive doen to 320px width viewport.
### Validators
----------------------------
- Each HTML file of this site has been put through the W3C HTML validator and had no errors or warnings returned.

![inxex.html validator](/assets/images/index-html-validator.jpeg)
![science.html validator](/assets/images/science-html-validator.jpeg)
![sign-up validator](/assets/images/sign-up-html-validator.jpeg)
- The CSS file behind the styling of this  site has been put through W3C CSS validator and had no errors returned.

![style.css validator](/assets/images/ccs-validator.jpeg)
### Performance and Accessibility
----------------------------
Please see below for the lighthouse test.

![Lighthouse](/assets/images/index-html-lighthouse.jpeg)
### Bugs
----------------------------
- Between 650px and 680px wide the animated gif in splash page is marginally too small for the space it exists in.

## Technologies Used
- HTML5
- CSS3
- FontAwesome
- Google Fonts


## Deployment
The Bee People site was published to GitHub pages.

![GitHub pages](/assets/images/github.jpeg)

## Credits
### Content
----------------------------
- Footer: The basic code structure and layout is borrowed from the Love Running walkthrough project. The icons used in the footer element are form FontAwesome.
- index.html section 2: The information provided to the user is taken from the WWF website.
- index.html section 3: The information provided tot he user was taken from two sources. 1)BBC Good Food 2)The Mayo Clinic.
- The index.html table element: The checkmarks and cross marks used in the table element are from FontAwesome.
- The science.html external links: The external links go to: 1)WWF 2)The British Beekeepers Society 3)National Geographic.
### Media
- All background images came from the stock image website Pexels.
- The science.html video element: The video is taken from the Kurzgesagt YouTube channel.
- The animated gif used in index.html were taken from Giphy. 
- The image at the top of this document was generated my Am I responsive.

## Acknowledgments
Brian Macharia, my Code Institue mentor.
The student support systems at Code Institute. 
