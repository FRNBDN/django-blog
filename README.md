# Codestar

Codestar is a blog website that is geared towards coding, with the administrator posting entries and users can like and comment them. The project is build with Django and is a walkthrough project from the Code Institutes Fullstack Developer Program.

[Deployed Project Link](https://djng-blog.herokuapp.com/)

![Responsive Mockup](#)

## Features 

### Existing Features

- __Navigation Bar__

  - Featured on all pages, the full responsive navigation bar includes links to, home, register, login and logout, the register and login links are only visible if logged out and the logout only if logged in. The logo also links to home.
  - This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

![Nav Bar](#)

- __The Home Page__

  - The home page lists all the blog posts showing the image of the post, the author, the title, likes count and also the excerpt if there is one, with 3 posts per row and 1 post per row on small screens.
  - This section introduces the user to the blog with all the recent posts

![Home Page](#)

- __Post Detail Page__

  - The post detail page shows the blogpost in its entirety and the comment section for the post, which includes previosu comments and if logged in, a comment posting form. 

![Post Detail Page](#)

- __Register Page__

  - Here the user creates an account with a username and password, with optional email.
  - The logged in benefits are being able to like and comment on posts. 

![Register Page](#)

- __The Sign In__

  - This is where the signs in to be able to like and comment on posts using their username and password.

![Sign In](#)

- __The Footer__ 

  - The footer section includes links to the relevant social media sites for Codestar. The links are not currently wired up since this is a fictional blog. 
  - The footer is valuable to the user as it encourages them to keep connected via social media

![Footer](#)

### Features Left to Implement

- Search feature - Useful in the future for users to find an old blogpost when there are hundreds of entries.

## Testing 

### Validator Testing 

- HTML
  - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fdjng-blog.herokuapp.com%2F)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fdjng-blog.herokuapp.com%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en)
- Python
  - Auto PEP8 was installed and used throughout the project, all issues were fixed as they appeard.


## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub) 

- The site was deployed to GitHub pages. The steps to deploy are as follows: 
  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://code-institute-org.github.io/love-running-2.0/index.html 

### Content 

- The icons in the project were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The images used in the project were provided by Code Institute
