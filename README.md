# Blockchain-Blog

![responsive design](media/taxes__1_.png)

When most people hear the word blockchain, which refers to a type of decentralized ledger technology, they immediately connect the term with cryptocurrencies. However, it is important to keep in mind that bitcoin just happened to be one of blockchain’s earliest and most popular applications; most experts believe that the potential for other applications of blockchain technology is vast.
___

## UX
This project is part of my [Code Institute](https://codeinstitute.net/) Full Stack Software Development studies. The idea was to create a blog page for users to register, comment and like various contents about different blockchain technology information. 

Main goals for users
* To make the website interactive for user wanting to learn all about blockchain technology.
    * Various external links are added for each blog posts. ✅

<br>

* Let users see the latest cryptocurrency prices from the newest coins. ✅
    * A price coin marquee widget was added to the header of the page generated from [CoinMarketCap](https://coinmarketcap.com/)

<br>

* As a user I want to.

    * Register ✅ 
    * Comment ✅ 
    * Like posts ✅
    * Be able to login ✅
    * Log out ✅
    * See how many likes on other content ✅
    * View all content as a user ✅

<br>

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

[Coinbase](https://www.coinbase.com/) and [Binance](https://www.binance.com/en) were used for content and images throughout the blog posts.
    
## [balsamiq wireframes](https://balsamiq.com/)

  * [Creating your first wireframe.](https://balsamiq.com/tutorials/articles/firstwireframe/)
    
    * A website wireframe, also known as a page schematic or screen blueprint, is a visual guide that represents the skeletal framework of a website. The term wireframe is taken from other fields that use a skeletal framework to represent 3 dimensional shape and volume. 

    * [Blockhain-Blog home page wireframe](https://github.com/Flow-matic/blockchain-blog/blob/main/media/wireframe%20home%20page.png?raw=true)

    * [Blog-page content](https://github.com/Flow-matic/blockchain-blog/blob/main/media/wireframes%20comment.png?raw=true)
___

## Features to add
   * Email sign up

     * However, email marketing has stood the test of time. Creating email newsletters is the most effective way to build stronger customer relationships, and grow your business revenue.

<br>

   * Newest conent

     * Keepping up to date with the industry, networking, social media, forums, and google alerts will be regularly researched. 

<br> 

   * All social media pages and links will be added at a later date for users to follow.

     * [Facebook](https://cryptolinks.com/facebook-cryptocurrency)
 
     * [Instagram](https://coinbound.io/25-top-crypto-instagram-influencers-you-should-be-following/)
 
     * [Youtube](https://coinbound.io/25-top-crypto-instagram-influencers-you-should-be-following/)
 
     * [Reddit](https://coinbound.io/best-crypto-subreddits/)
 
     * [Twitter](https://twitter.com/search?q=%23CRYPTO)

<br>

   * With over half of the world’s population using social media, platforms like Facebook, Instagram or Twitter a natural place to reach new and highly targeted potential customers.
___

## Technologies used

## Languages

- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/Cascading_Style_Sheets)
- [JavaScript](https://www.javascript.com/)
- [Python](https://www.python.org/)
___

## Frameworks, Libraries & Programs

<br>

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

<br>

The project was deployed to Heroku with the media files stored on Cloudinary.

### Setting up Heroku environment:

<br>

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

* [favicon.io](https://favicon.io/) was used to generate the browser icon, then the image was saved and uploaded to cloudinary.
___

## Credits 

<br>

Thanks to everyone involved at Code Institute for giving people the opportunity to the possibilities of a career change. From the student support, to the mentors available and everyone over at slack, getting this far with the course has been one of the most challenging things ive done.

<br>

* [Code Institute](https://github.com/Code-Institute-Org/python-essentials-template) for providing the walkthrough guided videos and code.

* [Favicon](https://favicon.io/) for the website favicon.

 * My go to website is always [W3Schools](https://www.w3schools.com/)

  * [Stackoverflow](https://stackoverflow.com/) best answers to your technical question.

  * [Wiki](https://en.wikipedia.org/wiki/Main_Page) Wikipedia is a free online encyclopedia.

  * [Slack](https://slack.com/) for that extra push and always help.

  * [MDN Web Docs](https://developer.mozilla.org/en-US/) best documentation on the web.

  * [Font Awesome](https://fontawesome.com/) is the Internet's icon library and toolkit, used by millions of designers, developers, and content creators.
___

<br>

Helpful Resources To Continue Learning About Blockchain
---
<br>

- [Ethereum](https://ethereum.org/) is the community-run technology powering the cryptocurrency ether (ETH) and thousands of decentralised applications.

- [Bitcoin](https://bitcoin.org/en/) uses peer-to-peer technology to operate with no central authority or banks.

- [Bitcoin whitepaper](https://bitcoin.org/bitcoin.pdf) Satoshi Nakamoto's original paper is still recommended reading for anyone studying how Bitcoin works.

- [Solidity](https://solidity.readthedocs.io/) is an object-oriented, high-level language for implementing smart contracts. Smart contracts are programs which govern the behaviour of accounts within the Ethereum state.

- [Blockchain explorer](https://www.blockchain.com/explorer) believe that in a decade the financial system of the internet — that is, commerce that happens on the internet — will be the largest financial system in the world. And it will be powered by crypto.

- [Coinbase](https://www.coinbase.com/learn) is a distributed company; all employees operate via remote work and the company lacks a physical headquarters.

- [Truffle Suite](https://www.trufflesuite.com/) A world class development environment, testing framework and asset pipeline for blockchains using the Ethereum Virtual Machine (EVM), aiming to make life as a developer easier.

- [Ganache](https://trufflesuite.com/ganache/) Quickly fire up a personal Ethereum blockchain which you can use to run tests, execute commands, and inspect state while controlling how the chain operates.

* [Binance Academy](https://academy.binance.com/en) Your one-stop guide to all things crypto. Whether you're a rookie trying to understand mining or a veteran looking to develop a trading strategy, we've got you covered.

* [Blockchain.com Exchange APIs](https://www.blockchain.com/api) Explore the REST API documentation for detailed examples of the various functionality offered, such as receiving real-time market data, requesting balance information, and performing trades.

* [CoinMarketCap](https://coinmarketcap.com/) Since its launch in 2013, CoinMarketCap has become one of the most powerful websites in the cryptocurrency space, being one of the most visited sites in the industry and a premier source of cryptocurrency market data.

* [Coinbase](https://www.coinbase.com/) Coinbase is a distributed company; all employees operate via remote work and the company lacks a physical headquarters. It is the largest cryptocurrency exchange in the United States by trading volume.

* [Live Coin Watch](https://www.livecoinwatch.com/) Complete cryptocurrency market coverage with live coin prices, charts and crypto market cap featuring 17399 coins on 463 exchanges.

* [CoinGecko](https://www.coingecko.com/) CoinGecko is the world’s largest independent cryptocurrency data aggregator with over 13,000+ different crypto-assets tracked across more than 500+ exchanges worldwide.

* [Messari](https://messari.io/) Messari brings transparency to the crypto-economy. Messari provides crypto market intelligence products that help professionals navigate crypto/Web3.

* [UseWeb3](https://www.useweb3.xyz/) is a platform for developers to explore and learn about Web3. Whether you're a new dev getting your hands dirty for the first time, or a seasoned developer making the transition into the Web3 space.

* [Best Websites For Programmers](https://github.com/sdmg15/Best-websites-a-programmer-should-visit) you must know to get always informed to do your technologies even better and learn new things. Here is a non-exhaustive list of some sites you should visit.
