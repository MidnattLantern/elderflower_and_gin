Elderflower and Gin
======

Elderflower and Gin is a catalogue of recipes for the cocktails enthusiast, looking for ideas and inspiration for drinks. Recipes are presented in an aesthetically exciting way, making the visitation experience last after the visit.

User Stories:
------
- The users who visit Elderflower and Gin seek ideas and inspiration for drinks and cocktails.
- The users can expect a unique and enjoyable experience that sets this site apart from other recipe sites.
- The users can expect finding ideas to be a straightforward experience, without the need to read lengthy paragraphs before finding the essential information.
- If the user finds a recipe that interests them, they can expect to learn more about it later.
- Saving recipes is possible through email submission, and the user can expect to share their thoughts through the “contact me” section.

Features:
------

Home Button:
- Present on all pages at a fixed position at the top left.
- On all but the home page it says "Back to Home Page".
- On the home page it says "Back to Top".

Welcome Sign:
- First thing that greets you in clear high contrast text.
- Greeting text, and a custom artwork of the mascot Elderflower.
- Desktop:
![desktop](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/desktop_home.png)
- Tablet:
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/lying_tablet_home.png)
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/standing_tablet_home.png)
- Phone:
![phone](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/phone_home.png)

Navigation Bar:
- Sends you to three sections of the home page: the "Cocktail Catalogue", the "About Us", and the "Contact Author" sections
![navigation_bar](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/navigation_bar_demostration.png)

Recipe section(s):
- PNG posters with consistent design.
- So far there are two categories: All and non-alcoholic.
- Both categories feature posters with clear text of the name of the drink.
- By default, the posters blend in with the background in soft monochrome grey.
- Upon hovering, the poster changes its appearance to full colour, high contrast, bigger scale, and box-shadow.
![hoverable_poster](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/hoverable_demostration.png)
- Due to the limited timeframe, only Hornan Tonic has a unique design. The others share a generic design.
- Clicking a recipe poster will redirect the visitor to another HTML page. Each recipe has its HTML.

About:
- Paragraph about the backstory behind this website, and what to expect
![about](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/about_us_demostratino.png)

Contact:
- The visitor can interact by filling in four boxes:
- A name
- An Email address
- Pick between four options
- Write text
- Submit
- When submitted, the visitor will be redirected to a confirmation page as a separate HTML.
![contact](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/contact_demostration.png)

Footer:
- Appearing in all pages
- a text and social media icons evenly centred
- Hover over a social media logo changes its appearance to another colour
- Clicking the social media logo sends the visitor to that website

Recipe page:
- Each recipe has its recipe page
- At the very top there's the drink's name
- To the left is the poster in full colour
- Next to the poster is a list of ingredients used for the drink
- Next or underneath the poster and ingredients section is a paragraph
- The paragraph appears either to the right or underneath the poster and recipe, depending on the screen size
- The paragraph tells a story about the drink, what it's like to experience drinking, and the suggested volume for each ingredient
- Desktop:
![desktop](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/desktop_recipe.png)
- Tablet:
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/lying_tablet_recipe.png)
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/standing_tablet_recipe.png)
- Phone:
![phone](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/static/images/readme_images/phone_recipe.png)

Recipe page request recipe:
- The visitor can fill out an email form
- Upon clicking the submit button, they'll be redirected to a confirmation page

The confirmation page:
- Box saying "thank you" with the mascot Elderflower
- paragraph letting the user know that they'll get a reply
- The home button appears again but is slightly bigger and underlined.
- The original home button is still at the top left for consistency

Red diamond pattern:
- Appears the left and right edges if the user is on a big screen.
- The warm hue and diamond pattern wrap the user inside a warm and cosy experience, similar to that of a café.

Testing:
------
Diversity of screen sizes:
- Using media queries, the appearance varies from device to device in a manner that's appropriate for such diversity.

Validator testing:
- No errors were returned when passing through the official W3C validator
- No errors were returned when passing through the official (Jigsaw) validator

Fixed bugs:
- The footer used to be long, but now it appears normal.
- The Galaxy Fold media query was excluded and the page looked awkward, now the media query includes the fold as the smallest tested device.

Deployment:
- The site was deployed to GitHub pages. The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
- From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found here - https://github.com/MidnattLantern/elderflower_and_gin.git

Credits:
- The social media icons appearing at the footer were borrowed from fontawesome.com.
- The theme font is "Kurale", borrowed from fonts.google.com. Kurale is permitted to be used in this manner.
- All posters and artworks were designed and made by the same developer behind Elderflower and Gin.
- All text and paragraphs were written by the same developer behind Elderflower and Gin. GrammarlyGO was co-used as an advice tool on phrasing and choice of words.
- The recipes behind "Sparkling Liqud" and "Irish Coffee" are well-known drinks. The recipes behind "Hornan Tonic" and "Gessi Tonic" were suggested by ChatGPT.

Wireframes:
------
Visualisation for front-end appearance was sketched with art software.

Technology:
------
- Everything was developed and designed with a computer running macOS.
- Illustrations and other visual elements were designed using a Wacom tablet.
- All code was written on Microsoft Visual Studio Code.
- Elderflower and Gin is hosted by GitHub.
- All code was tested, debugged, and simulated through Microsoft Edge.
- Media queries were tested for the following through Microsoft Edge: "Galaxy fold 280x653", "iPhone 12 Pro 390x844", and "iPad Mini 768x1024".
- Some paragraphs were assisted with GrammarlyGO and ChatGPT.
- The theme font "Kurals" was borrowed from Google Fonts.
- Social media icons were borrowed from Font Awesome.
- Graphics and wireframes were designed using Clip Studio Paint, Affinity Photo 2, and Affinity Designer 2.

Deployment:
------
- Deployed to GitHub
- Developed and deployed through Microsoft Visual Studio Code