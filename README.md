# Hangman

This project aims to recreate the game "Hangman" with a minimal aesthetic, dynamic images and life counter and some simple category and hint options.

![Responsice](assets/images/responsive.png)

## Features 

### Existing Features

- __Hangman Logo and Heading__

  - A simple but iconic logo to represent the game and a googlefont heading give a minimal aesthetic.

![Logo](media/love_maths_logo.png)

- __The Categories__

  - The user can see three categories and an indication that this is where to start. Clicking on one of them will prep the game area with a hidden word but reveal the word length. It will also clear the board in any state and get back to a fresh state, ready to play. The letters are reset to red, the images reset to the beginning, the hint is hidden and changed to the new word and the guess attempts are reset to 7.

![Categories](media/love_maths_icons.png)

- __The Hangman State section__

  - The image of the eponyous hangman, the images dynamically change every time an incorrect guess is taken. There are 7 images building up the hangman piece by piece and then 1 final image showing the fail state of the poor hangman if you fail to guess the word after 7 incorrect letters. Undeneath is a number of how many guesses you have left.

![Hangman State](media/love_maths_question.png)

- __The Game Area__

  - This section has the word you are guessing itself and shows you the length of the word, as well as the letters of the alphabet to click for each attempt. The letters grey out and cannot be guessed twice to prevent wasting guesses or time. 

![Game Area](media/love_maths_answer.png)

- __The Hint Area__

  - This section has a hidden hint that the user can click on to help with guessing the words. The hint is reset and hidden when you choose a category.

![Hint Area](media/love_maths_answer.png)

### Features Left to Implement

- Separate the reset feature from the category feature.
- Add more categories and ways to expand on lists of words that can be used.
- Add more variety of images so you get different hangmen or themed images depending on the category.
- Automatically pick a new category and reset on win.

## Testing 

Using chrome dev tools the hangman site was tested in responsive, 4k, iphone XE, iphone SR, iphone 12, samsung galaxy s8, samsung galaxy s20, ipad air and ipad mini to ensure the layout was suitably responsive and there were no out of place elements.

[iPhone 12](assets/images/media/iphone-12.png)

[Samsung Galaxy S8](assets/images/samsung-galaxy-s8.png)

[iPad Air](assets/images/iPad-Air.png)

### Validator Testing 

- HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-maths%2F)
- CSS
    - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-maths%252F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- JavaScript
    - No errors were found when passing through the official [Jshint validator](https://jshint.com/)
      - The following metrics were returned: 
      - There are 11 functions in this file.
      - Function with the largest signature takes 2 arguments, while the median is 0.
      - Largest function has 10 statements in it, while the median is 3.
      - The most complex function has a cyclomatic complexity value of 4 while the median is 2.

### Unfixed Bugs

- Due to not fully separating the reset feature from the category buttons, the game starts in a state where you cannot instantly play without clicking the category buttons to play which may cause some users to try to start playing right away without reading the text indicating to click the category. 

- Related to this, the letters turn gray giving misleading feedback before you click a category.

## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://adam-daly.github.io/Project-2-Hangman/


## Credits 

### Content 

- Flexbox css: https://www.w3schools.com/css/css3_flexbox_container.asp
- HTML Framework and Javascript starting point: Code Institutes Love Maths Project
- Hangman Specific Help :
    - https://codepen.io/cathydutton/pen/JjpxMm
    - https://www.youtube.com/watch?v=T6uht1A0114


### Media

- Hangman Logo : https://www.iconfinder.com/iconsets/brain-games
- Hangman Stages: https://thecityofregalia.tumblr.com/post/94905917024/hangman

## Other General Project Advice

Below you will find a couple of extra tips that may be helpful when completing your project. Remember that each of these projects will become part of your final portfolio so it’s important to allow enough time to showcase your best work! 

- One of the most basic elements of keeping a healthy commit history is with the commit message. When getting started with your project, read through [this article](https://chris.beams.io/posts/git-commit/) by Chris Beams on How to Write  a Git Commit Message 
  - Make sure to keep the messages in the imperative mood 

- When naming the files in your project directory, make sure to consider meaningful naming of files, point to specific names and sections of content.
  - For example, instead of naming an image used ‘image1.png’ consider naming it ‘landing_page_img.png’. This will ensure that there are clear file paths kept. 

- Do some extra research on good and bad coding practices, there are a handful of useful articles to read, consider reviewing the following list when getting started:
  - [Writing Your Best Code](https://learn.shayhowe.com/html-css/writing-your-best-code/)
  - [HTML & CSS Coding Best Practices](https://medium.com/@inceptiondj.info/html-css-coding-best-practice-fadb9870a00f)
  - [Google HTML/CSS Style Guide](https://google.github.io/styleguide/htmlcssguide.html#General)

Getting started with your Portfolio Projects can be daunting, planning your project can make it a lot easier to tackle, take small steps to reach the final outcome and enjoy the process! 