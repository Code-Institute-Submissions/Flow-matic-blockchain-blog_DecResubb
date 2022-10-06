# Blockchain-Blog

![responsive design](media/taxes__1_.png)

When most people hear the word blockchain, which refers to a type of decentralized ledger technology, they immediately connect the term with cryptocurrencies. However, it is important to keep in mind that bitcoin just happened to be one of blockchain’s earliest and most popular applications; most experts believe that the potential for other applications of blockchain technology is vast.
___

## UX
This project is part of my [Code Institute](https://codeinstitute.net/) Full Stack Software Development studies. The idea was to create a blog page for users to register, comment and like various contents about different blockchain technology information. 

* Main Goals for users
    * To make the website interactive for user wanting to learn all about blockchain technology.
        * Various external links are added for each blog posts. ✅
    * Let users see the latest cryptocurrency prices from the newest coins. ✅
        * A price coin marquee widget was added to the header of the page generated from [CoinMarketCap](https://coinmarketcap.com/)
    * As a user I want to.
        * Register ✅ 
        * Comment ✅ 
        * Like posts ✅
        * Be able to login ✅
        * Log out ✅
        * See how many likes on other content ✅
        * View all content as a user ✅
* Admin users can.
    * Add/edit/delete posts ✅
    * Create groups/users ✅
    * add attachments ✅
    * Social accounts ✅
    * Aprove/delete selected comments ✅
___

## Design
As a base guide I used code institute walkthrough videos for the design process.
   * Imagery used
        * I wanted to use cartoon style images throughout each blog page.
    

___

## Features to add
   * Email sign up

     * However, email marketing has stood the test of time. Creating email newsletters is the most effective way to build stronger customer relationships, and grow your business revenue.
    
   * Newest conent

     * Keepping up to date with the industry, networking, social media, forums, and google alerts will be regularly researched. 
___

## Technologies used

## Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [JavaScript](https://www.javascript.com/)
- [Python](https://www.python.org/)

## Frameworks, Libraries & Programs

- [**Django**](https://www.djangoproject.com/)
  - Python Web framework used to build the site.

- [**Gitpod**](https://www.gitpod.io/)
  - Gitpod terminal was used to commit and push to GitHub.

- [**GitHub**](https://github.com/)
  - GitHub is used to store the project code after being pushed from Git.

- [**Heroku**](https://www.heroku.com/)
  - Heroku is the app platform I deployed my project to.

- [**Heroku Postgres**](https://www.heroku.com/postgres)
  - Heroku’s reliable and powerful database used to store the data for my deployed Heroku App.

- [**Bootstrap 4**](https://getbootstrap.com/)
  - Bootstrap was used to assist with the responsiveness and styling of the website using design templates.

- [**gunicorn**](https://gunicorn.org/)
   - WSGI server used to take care of everything happening between the web server and web application.

- [**psycopg2**](https://pypi.org/project/psycopg2/)
    - PostgreSQL database adapter

- [**Google fonts**](https://fonts.google.com/)
    - Google Fonts makes it easy to bring personality and performance to your websites and products.

- [**Font Awesome 4.7.0**](https://fontawesome.com/)
  - Font Awesome was used to add icons for aesthetic and UX purposes.

- [**W3 Validator**](https://validator.w3.org/#validate_by_input) and [**W3C CSS Validator**](https://jigsaw.w3.org/css-validator/#validate_by_input)
  - Used to validate my HTML and CSS files

- [**JShint**](https://jshint.com)
    - Used to validate JS code
___

## Deployment 

The project was deployed to Heroku with the media files stored on Cloudinary.

### Setting up Heroku environment:

Make sure you add a procfile to your root directory!

   * The Procfile is always a simple text file that is named [Procfile](https://devcenter.heroku.com/articles/procfile) without a file extension. For example, Procfile.txt is not valid. The Procfile must live in your app’s root directory. It does not function if placed anywhere else.

   * Once you have your [account](https://www.heroku.com/) ready, login with your credentials.

   * Click New on the top right corner and select “Create new app”.

   * Give your app a name (This will be included in the public URL for your application) and click Create app.

   * This step will take you to the dashboard of your app. Open Deploy tab and scroll to the “Deployment method” section.

   * Select GitHub as the method.

   * It will show a “Connect to GitHub” option where we can provide our GitHub repository. If you are doing it for the first time, Heroku will ask permission to access your GitHub account.

   * Here, you can search for your GitHub repository and click connect:

   * If it’s able to find and connect to the GitHub repository, the Deployment section will show up where you can select if you want Automatic Deployment (as soon as the changes are pushed to GitHub, Heroku will pick them up and deploy) or Manual Deployment.

   * Click Enable Automatic Deploys (because it’s less overhead for demo apps :) ). You can also select the GitHub branch if you need to, deploy from the main branch.

### Cloudinary

   * create your account with cloudinary first and follow these steps for storing your [media files](https://cloudinary.com/documentation/how_to_integrate_cloudinary). 