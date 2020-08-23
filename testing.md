# Face Fodder Testing Documentation

## Table of Contents
* [User Story Testing](https://github.com/caseybanks/ms1-face-fodder/blob/master/testing.md#user-story-testing)
* [Manual Testing of Features](https://github.com/caseybanks/ms1-face-fodder/blob/master/testing.md#manual-testing-of-features)
* [Peers Review Testing](https://github.com/caseybanks/ms1-face-fodder/blob/master/testing.md#peers-review-testing)
* [W3C Validation Testing]()
    - [HTML]()
    - [CSS]()
* [Responsiveness Testing]()

## User Story Testing
> User story 1 - _"I love the natural facemasks I buy from Lush and would like to learn how to make my own, but don't know how."_

Manual testing competed for a user with tired skin scenario:

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page |Pass|
|2| User scrolls down to the "_HOME DIY SOLUTIONS FOR ..._" section which has 3 image options: dry skin, tired skin, acne|Pass|
|3| User clicks on the tired skin image, which redirects them to a recipe on how to make a "_FACE MASK FOR TIRED SKIN_"|Pass|

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User clicks on the "_Beauty Recipe Book_" which then displays a dropdown option for "_DIY Beauty Recipes_"|Pass|
|3| User clicks on the dropdown item "_DIY Beauty Recipes_" which then gives further options "_for Dry Skin/ Tried Skin/ Acne_"|Pass|
|4| User clicks on the "_for Tired Skin_" option which redirects them to a recipe on how to make a "_FACE MASK FOR DRY SKIN_"|Pass|

> User story 2 - _"My skin is really dry, I wonder what could help with the dryness?"_

Manual testing competed for a user with dry skin scenario:

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User scrolls down to the "_HOME DIY SOLUTIONS FOR ..._" section which has 3 image options: dry skin, tired skin, acne|Pass|
|3| User clicks on the dry skin image, which redirects them to a recipe on how to make a "_FACE MASK FOR DRY SKIN_"|Pass|

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User clicks on the "_Beauty Recipe Book_" which then displays a dropdown option for "_DIY Beauty Recipes_"|Pass|
|3| User clicks on the dropdown item "_DIY Beauty Recipes_" which then gives further options "_for Dry Skin/ Tried Skin/ Acne_"|Pass|
|4| User clicks on the "_for Dry Skin_" option which redirects them to a recipe on how to make a "_FACE MASK FOR DRY SKIN_"|Pass|

Manual testing competed for a user with acne scenario:

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User scrolls down to the "_HOME DIY SOLUTIONS FOR ..._" section which has 3 image options: dry skin, tired skin, acne|Pass|
|3| User clicks on the acne image, which redirects them to a recipe on how to make a "_FACE MASK FOR SKIN WITH ACNE_"|Pass|

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User clicks on the "_Beauty Recipe Book_" which then displays a dropdown option for "_DIY Beauty Recipes_"|Pass|
|3| User clicks on the dropdown item "_DIY Beauty Recipes_" which then gives further options "_for Dry Skin/ Tried Skin/ Acne_"|Pass|
|4| User clicks on the "_for Acne_" optnion which redirects them to a recipe on how to make a "_FACE MASK FOR SKIN WITH ACNE_"|Pass|

> User story 3 - _"I often have avocado left over from making my green smoothies, I've heard avocado is really good if apply it directly onto my skin but I'm not sure."_

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User clicks on the "_Beauty Recipe Book_" which then displays a dropdown option for "_Ingredients_"|Pass|
|3| User clicks on the dropdown item "_Ingredients_" which then redirects them to a informative page containing the benefits of Avocado for your skin|Pass|

> User story 4 - _"I've tried a few recipes on the Face Fodder website and love them, but I have a question I need to ask?"_

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on home page|Pass|
|2| User clicks on the "_Contact_" menu option in the heading which redirects them to a page with a contact form |Pass|
|3a| User tries to submit the form without entering mandatory fields name and email: Gets validation alerts notifications informing the user that name and email fields are required |Pass|
|3b| User enters in a valid name and email address with an @ symbol, the form is submitted successfully and a success message returned |Pass|

> User story 5 - _"When I'm cooking in the kitchen, I often use my iPad to view recipes or print them off for convenience"_

| User Step | Description | Pass or Fail |
|:----------|:------------|:------------:|
|1| User lands on a recipe page: dry skin/ tired skin/ acne. A download button is available to click.|Pass|
|2| User clicks the recipe download button which opens up in a new tab/ window to print or save as an image or PDF |Pass|

## Manual Testing of Features

The following features were manually tested:

* Navigation menu links: Home, Beauty Recipe Book, Ingredients, DIY Beauty Recipes, for Dry Skin, for Tired Skin, for Acne, Contact, all take a user to the correct location when clicked - Passed
* The 3 images in DIY solution section on the Home page, all redirect to the correct recipe - Passed
* Each carousel item has an image link (recipe or ingredient) and more information/ recipe button that redirects to the ingredients page or recipe page - Passed
* Social media icons, when clicked, open up a new tab/ window to the social URL address - Passed
* The Contact Form has been tested as part of User story 5 - Passed

## Peers Review Testing

Review by _Miranda_ on _16th August 2020_:
> Hey @Casey! Great work on your first milestone project. You've created a beautiful design with a great colour scheme and a clean layout.
I have a few comments for you to consider:
>1. Consider allowing users to click on the logo to return to the home page. This is standard practice and will add to the user experience for ease of navigation.
>1. The 'form submission' feature you've added is brilliant! Really well done. One small comment about it though: perhaps consider moving the message to the top of the screen so the user immediately sees that it was submitted successfully? It'll save them having to scroll down before seeing whether it was successfully submitted or not.
>1. A really minor detail, but the images on the home page aren't aligned to the center on screens smaller than 767px. I think that can be quickly solved by targeting the margins with a media query.
>1. I found the 'beauty benefits' quite small to read - it could just be a taste and preference thing, but consider making the font slightly larger as I think the information is good for the user to read easily.

Review by _Karina_ on _16th August 2020_:
>I really love the clean design and your logo is brilliant! I have a few points that might be helpful:
>1. The focus outline is the default blue and it clashes with your lovely clean green and white tones. I would make it so that that colour is the green of your logo. You can see this clearly when you click on your hamburger navigation, or by tabbing through the site.
>1. I would add a :hover effect to the social icons - maybe a colour change or something?
>1. Between around 628-768px screen width your social icons stack 3 on top, 1 on the bottom - design-wise I think keep the 2 and 2 block design or force 4 in a row sooner - 3 &1 looks somewhat unbalanced.
>1. I'm not sure you need the email address in your footer, given that you have a contact page? Maybe you could do nav-links there instead? I do see that design-wise it's balancing the social icons.
>1. the grey copyright bar underneath your footer feels tonally unnecessary - I might make it the same colour as the footer with maybe a thin divider line? Or if not, give the copyright line a little bit more padding.
>
>These are mostly design-based considerations as I think your site is really lovely, and worked perfectly for me on desktop.
>
>On mobile the "dry skin ---> acne" images are slightly off-centre, as are the images of ginger and avocado, the latter also have a wafer thin line down their right side.

Review by _Neringa_ on _16th August 2020_:
>@Casey I love the idea of your MS1, super cool! The site looks lovely! I have looked at it on my hp laptop and sizing looks good. One thought - when I press on contact it shows the hero image and I don't see right away that I need to scroll down to see the form to complete. That's my only think that I could say, however if you're happy with it that's all good!

To address the peer review comments and bugs I have raised the following bugs as To Do in the [Git Project Management tool](https://github.com/caseybanks/ms1-face-fodder/projects/1):
1. [FF1: Add Home link to Logo image](https://github.com/caseybanks/ms1-face-fodder/issues/1)
1. [FF2: Make form submit success page clearer](https://github.com/caseybanks/ms1-face-fodder/issues/2)
1. [FF3: On small screen the "HOME DIY SOLUTIONS FOR ..." section does not center align images](https://github.com/caseybanks/ms1-face-fodder/issues/3)
1. [FF4: Make Beauty Benefits text bigger on Ingredients page](https://github.com/caseybanks/ms1-face-fodder/issues/4)
1. [FF5: When a dropdown nav item is clicked it is highlighted blue](https://github.com/caseybanks/ms1-face-fodder/issues/5)
1. [FF6: Add a :hover effect to the social icons](https://github.com/caseybanks/ms1-face-fodder/issues/6)

## W3C Validation Testing

### HTML

Using direct input into the [Markup Validation Service](https://validator.w3.org/), the following bugs were highlighted and fixed:

1. [W3C Footer error: Incorrect <h7> tag](https://github.com/caseybanks/ms1-face-fodder/issues/13)
1. [W3C Markup Contact form errors](https://github.com/caseybanks/ms1-face-fodder/issues/14)

|Page|Pass or Fail|W3C Comments|
|:---|:----------:|:-----------|
|index.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|
|dryskin.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|
|tiredskin.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|
|acne.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|
|ingredients.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|
|contact.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|
|success.html|Pass| With a warning: Section lacks heading. Consider using h2-h6 elements to add identifying headings to all sections.|

The warning for lack of heading is for my Hero image section, which does not require a heading.

### CSS

Using direct input into the [CSS Validation Service](https://jigsaw.w3.org/css-validator/), no errors were found in my style.css file.

## Responsiveness Testing

[Am I Responsive?](http://ami.responsivedesign.is/)

[Responsinator](https://www.responsinator.com/)