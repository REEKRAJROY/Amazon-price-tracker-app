# Amazon-price-tracker-app

An Amazon Price tracking notifier which scraps off prices from Amazon's site sends an email to the host whenever price of a particular item drops
below a set threshold. Node has been used to create the JavaScript application. Scraping has been implemented using nightmare library, sendgrid
has been used to implement mailing services. dotenv library is used to handle the .env files.

### 🚀️ Setting up 

### `npm i nightmare @sendgrid/mail` 
To import nightmare and sendgrid libraries.




### `npm i dotenv`
To import dotenv library

Api key from sendgrid copied inside varaible in .env file and set in parser.js.

Set up a mailing service where mail can be received. [temp-mail.org](https://temp-mail.org/en/) is a good option.

Simillarly, select an email from where the alert will be send.

### `node parser.js https://www.amazon.in/itemlink price_threshold`
To run the app
