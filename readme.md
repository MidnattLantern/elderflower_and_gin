Elderflower and Gin
======

Elderflower and Gin is a catalogue of recipes for the cocktails enthusiast, looking for ideas and inspiration for drinks. Recipes are presented in an aesthetically exciting way, making the visitation experience last after the visit.

User Stories:
------
- As a visitor who is a cocktail enthusiast looking for inspiration, I expect that Elderflower and Gin will let me find ideas and inspiration.
- As a visitor who is a cocktail enthusiast, I expect a unique and enjoyable experience that sets this site apart from other recipe sites.
- As a visitor who is a cocktail enthusiast, I expect that finding ideas is as straightforward and instant as possible, without the need to read lengthy paragraphs before finding the essential information.
- As a visitor who is a cocktail enthusiast, if I find a recipe that interests me, I expect to learn more about it later.
- As a visitor who is a cocktail enthusiast, I expect that I'm able to get a recipe sent to my email by submitting an email address in a field, as well as getting clear confirmation that my request went through.
- As a scout or business person who is looking to recruit someone with confidence in web development or graphic design, I expect that I'm able to easily reach the author behind Elderflower and Gin by submitting my email, my name and some text in a message field.
- As a critic, I expect that I'm able to give feedback about a recipe by submitting my email, my name, and some text in a text field where I can write my opinions on a drink, or suggest a new drink.
- As a scout or business person who is looking to recruit someone with confidence in graphic design, I expect that I'm able to find the author on other platforms, such as Instagram or ArtStation.
- As a visitor with certain preferences, I expect to find a category that excludes any traces of alcohol.

Wireframes:
------
- Visualisation for front-end appearance was sketched with art software.
- The following images are wireframes to support as visual references during the early phase:
![wireframe1](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/wireframe1.png)
![wireframe2](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/wireframe2.png)
![wireframe3](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/wireframe3.png)
![wireframe4](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/wireframe4.png)
- This one is a general guide to what artistic direction to follow for the characters (painted by Alma as well)
![wireframe5](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/wireframe5.jpg)

Testing:
------
Diversity of screen sizes:
- Using media queries, the appearance varies from device to device in a manner that's appropriate for such diversity.
- Here's an example for the home page:
- Desktop:
![desktop](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/desktop_home.png)
- Tablet:
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/lying_tablet_home.png)
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/standing_tablet_home.png)
- Phone:
![phone](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/phone_home.png)

Validator testing:
- No errors were returned when passing through the official W3C validator
- No errors were returned when passing through the official (Jigsaw) validator

Fixed bugs:
- The footer used to be long, but now it appears normal.
- The Galaxy Fold media query was excluded and the page looked awkward, now the media query includes the fold as the smallest tested device.

Credits:
- The social media icons appearing at the footer were borrowed from fontawesome.com.
- The theme font is "Kurale", borrowed from fonts.google.com. Kurale is permitted to be used in this manner.
- All posters and artworks were designed and made by the same developer behind Elderflower and Gin.
- All text and paragraphs were written by the same developer behind Elderflower and Gin. GrammarlyGO was co-used as an advice tool on phrasing and choice of words.
- The recipes behind "Sparkling Liqud" and "Irish Coffee" are well-known drinks. The recipes behind "Hornan Tonic" and "Gessi Tonic" were suggested by ChatGPT.
- The following HTML code was borrowed from https://fontawesome.com/ :
- <script src="https://kit.fontawesome.com/4b0d3e328e.js" crossorigin="anonymous"></script>
- The following CSS code was borrowed from https://fontawesome.com/ :
- 'https://fonts.googleapis.com/css2?family=Kurale&display=swap'

Deployment:
------

GitHub deployment:
- The site was deployed to GitHub pages. Here's how to deploy:
- In the GitHub repository, navigate to the settings tab, it looks like a cogwheel,
- From the source section drop-down menu, select the master branch,
- When the master branch is selected, the page should provide a link to the website.
- The repository link can be found here - https://github.com/MidnattLantern/elderflower_and_gin.git
- The live link can be found here - https://midnattlantern.github.io/elderflower_and_gin/

MS Visual Studio Code deployment:
- Here's how to deploy from MS Visual Studio Code:
- make sure you've signed in,
- on the source control section, click “Initialize Repository”,
- For any changes, open the terminal, type "git add .", then "git commit -m """, finally "git push".

Features:
------

Home Button:
- Present on all pages at a fixed position at the top left.
- On all but the home page it says "Back to Home Page".
- On the home page it says "Back to Top".
![home_button_demostration](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/home_button_demostration.png)

Welcome Sign:
- First thing that greets you in clear high contrast text.
- Greeting text, and a custom artwork of the mascot Elderflower.
- Desktop:
![desktop](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/desktop_home.png)
- Tablet:
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/lying_tablet_home.png)
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/standing_tablet_home.png)
- Phone:
![phone](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/phone_home.png)

Navigation Bar:
- Sends you to three sections of the home page: the "Cocktail Catalogue", the "About Us", and the "Contact Author" sections
![navigation_bar](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/navigation_bar_demostration.png)

Recipe section(s):
- PNG posters with consistent design.
- So far there are two categories: All and non-alcoholic.
![all_category](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/all_recipe_category_demostration.png)
![no_alcohol_category](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/no_alcohol_category_demostration.png)
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
- The visitor can interact by filling in four boxes and a submit button in the following order:
- 1. A name or handle
- 2. An Email address
- 3. Pick between four options
- 4. Write text
- 5. Submit
![contact](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/contact_demostration.png)
- When submitted, the visitor will be redirected to a confirmation page as a separate HTML.
![confirmation](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/confirmation_demostration.png)

Footer:
- Appearing in all pages
- a text and social media icons evenly centred
- Hover over a social media logo changes its appearance to another colour
- Clicking the social media logo sends the visitor to that website in a new browser tab
![footer](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/footer_demostration.png)

Recipe page:
- Each recipe has its recipe page
- At the very top there's the drink's name
- To the left is the poster in full colour
- Next to the poster is a list of ingredients used for the drink
- Next or underneath the poster and ingredients section is a paragraph
- The paragraph appears either to the right or underneath the poster and recipe, depending on the screen size
- The paragraph tells a story about the drink, what it's like to experience drinking, and the suggested volume for each ingredient
- Desktop:
![desktop](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/desktop_recipe.png)
- Tablet:
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/lying_tablet_recipe.png)
![tablet](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/standing_tablet_recipe.png)
- Phone:
![phone](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/phone_recipe.png)

Recipe page request recipe:
- The visitor can fill out an email form
![request](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/recipe_request_demostration.png)
- Upon clicking the submit button, they'll be redirected to a confirmation page
![confirmation](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/confirmation_demostration.png)

The confirmation page:
- Box saying "thank you" with the mascot Elderflower
- paragraph letting the user know that they'll get a reply
- The home button appears again but is slightly bigger and underlined.
- The original home button is still at the top left for consistency
![confirmation](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/confirmation_demostration.png)

Red diamond pattern:
- Appears the left and right edges if the user is on a larger device.
- Although it has no practical purpose, it contributes a lot to the emotional experience for users on a larger device.
![red_diamond](https://raw.githubusercontent.com/MidnattLantern/elderflower_and_gin/main/readme_images/red_diamond_demostration.png)

Future features:
------
- Submitting feedback for now doesn't do anything. This could be updated so that each letter will be stored for the developer(s) to read.
- Requesting a recipe won't send a recipe to the email the user provided. This could be updated so that the recipe is sent to their provided email.
- Unique poster artwork design for Gessi Tonic, Irish Coffee, and Sparkling Liquid.
- More Recipes
- More categories
- Filter section by the top, such as filtering out alcoholic drinks, or only show sweet drinks
- Alcohol label to specify what drinks and ingredients contain alcohol

Typography and colour scheme:
------
Typography:
- Two fonts are being used: Kurale, and Arial.
- Kurale is the theme font. It appears for shorter text.
- Arial is the paragraph font. Its minimalist design and lack of stimulation make it easy and light to read for a length of time. It's quite boring, however, so it's used sparingly.

Colour scheme:
- The theme colour is red.
- The white and black are off-white, and dark blue. This creates an impression of 'down to earth modesty'.
- Each poster has its colour scheme. What colour(s) depends on the desired impression?
- Because each poster's colour scheme is so diverse, every poster is grey on the home page until hovering, this is to prevent clashing user experience.

Technology:
------
- Everything was developed and designed with a computer running macOS.
- Illustrations and other visual elements were designed using a Wacom tablet.
- All code (except for font awesome and Google fonts) was written on Microsoft Visual Studio Code by Alma.
- Elderflower and Gin is hosted by GitHub.
- All code was tested, debugged, and simulated through Microsoft Edge.
- Media queries were tested for the following through Microsoft Edge: "Galaxy fold 280x653", "iPhone 12 Pro 390x844", and "iPad Mini 768x1024".
- Some paragraphs were assisted with GrammarlyGO and ChatGPT.
- The theme font "Kurals" was borrowed from Google Fonts.
- Social media icons were borrowed from Font Awesome.
- Graphics and wireframes were designed using Clip Studio Paint, Affinity Photo 2, and Affinity Designer 2, by Alma.
- Grammar checking was done using Grammarly.

Deployment:
------
- Deployed to GitHub
- Developed and deployed through Microsoft Visual Studio Code