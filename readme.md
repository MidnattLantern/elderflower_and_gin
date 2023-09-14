Elderflower and Gin
======

Elderflower and Gin is a catalogue of recipes for the cocktails enthusiast, looking for ideas and inspiration for drinks. Recipes are presented in an aesthetically exciting way, making the visitation experience last after the visit.

User Stories:
------
- The users who visit Elderflower and Gin seek ideas and inspiration for drinks and cocktails.
- The users can expect a unique and enjoyable experience that sets this site apart from other recipe sites.
- The users can expect finding ideas to be an straight-forward experience, without the need to read lengthy paragraphs before finding the essential information.
- If the user find a recipe that interests them, they can expect to learn more about it later.
- Saving recipes is possible through email submission, and the user can expect to share their thoughts through the “contact me” section.

Features:
------

Home Button:
- Present on all pages at a fixed position at the top left.
- On all but the home page it says "Back to Home Page".
- On the home page it says to "Back to Top".

Welcome Sign:
- First thing that greets you in clear high contrast text.
- Greeting text, and a custom artwork of the mascot Elderflower.
Desktop:
![desktop](../elderflower_and_gin/static/images/readme_images/desktop_home.png)
Tablet:
![tablet](../elderflower_and_gin/static/images/readme_images/lying_tablet_home.png)
![tablet](../elderflower_and_gin/static/images/readme_images/standing_tablet_home.png)
Phone:
![phone](../elderflower_and_gin/static/images/readme_images/phone_home.png)

Navigation Bar:
- Sends you to three sections of the home page: the "Cocktail Catalogue", the "About Us", and the "Contact Author" sections

Recipe sectiion(s):
- PNG posters with consistent design.
- So far there are two categories: All and non-alcoholic.
- Both categories feature posters with clear text of the name of the drink.
- By default the posters blend in with the background in soft monochrome grey.
- Upon hovering, the poster change appearance to full colour, high contrast, bigger scale, and box shadow.
- Due to limited timeframe, only Hornan Tonic has a unique design. The others share a generic design.
- Clicking a recipe poster will redirect the visitor to another html page. Each recipe have their own html.

About:
- Paragraph about a backstory behind this website, and what to expect

Contact:
- The visitor can interact by filling four boxes:
- A name
- An Email address
- Pick between four optoins
- Write text
- Submit
- When submitted, the visitor will be redirected to a confitmation page as a seperate html.

Footer:
- Appearing in all pages
- a text and social media icons evenly centerd
- Hover over a social media logo changes its appearance to another colour
- Clicking the social media logo sends the visitor to that website

Recipe page:
- Each recipe have its own recipe page
- At the very top there's the drink's name
- To the left is the poster in full colour
- Next to the poster is a list of ingredients used for the drink
- Next or underneath the poster and ingredients section is a paragraph
- The paragraph appeats either to the right or underneath the poster and recipe, depending on screen size
- The paragraph tell a story about the drink, what it's like to experience drinking, and suggested volume for each ingredient

Recipe page request recipe:
- The visitor can fill an email form
- Upon clicking the submit button, they'll be redirected to a confirmation page

The confirmail page:
- Box saying "thank you" and the mascot Elderflower seen at the home page
- paragraph letting the user know that they'll get a reply
- The home button appears again but slightly bigger and underlined.
- The original home button is still at the top left for consistency

Red diamond pattern:
- Appears the the left and right edges if the user is on a big screen.
- The warm hue and diamond pattern wraps the user inside a warm and cozy experience, similar to that of a café.

Testing:
------
Diversity of screen sizes:
- Using media queries, the appearance vary from device to device in a manner that's appropriate for such diversity.

Validator testing:
- No errors were returned when passing trough the official W3C validator
- No errors were returned when passing trough the official (Jigsaw) validator

Fixed bugs:
- Footer used to be long, now it appears normal.
- Galaxy Fold media query was excluded and the page looked awkward, now the media query includes the fold as the smallest tested device.

Deployment:
- The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found here - https://github.com/MidnattLantern/elderflower_and_gin.git

Credits:
- The social media icons appearing at the footer was borrowed from fontawesome.com.
- The theme font is "Kurale", borrowed from fonts.google.com. Kurale is permitted to be used in this manner.
- All posters and artworks were designed and made by the same devloper behind Elderflower and Gin.
- All text and paragraphs were written by the same developer behind Elderflower and Gin. GrammarlyGO was co-used as an advice tool on phrasing and choice of words.
- The recipes behind "Sparkling Liqud" and "Irish Coffee" are well known drinks. The recipes behind "Hornan Tonic" and "Gessi Tonic" was suggested by ChatGPT.

Wireframes:
------
Visualisation for front end appearance was sketched with art software.

Technology:
------
- Everything was devloped and designed with a computer running macOS.
- Illustrations and other visual elements was designed using a Wacom tablet.
- All code was written on Microsoft Visual Studio Code.
- Elderflower and Gin is hosted by GitHub.
- All code was tested, debugged, and simulated trough Microsoft Edge.
- Media queries was tested for following trough Microsoft Edge: "Galaxy fold 280x653", "iPhone 12 Pro 390x844", "iPad Mini 768x1024".
- Some paragraphs was assisted with GrammarlyGO and ChatGPT.
- The theme font "Kurals" was borrowed from Google Fonts.
- Social media icons was borrowed from Font Awesome.
- Graphics and wireframes was designed using Clip Studio Paint, Affinity Photo 2, and Affinity designer 2.

Deployment:
------
- Deployed to GitHub
- Developed and deployed trough Microsoft Visual Studio Code