# Question

At Lohono Stays, we provide villas on rent to the prospective clients. Each villa has a calendar associated with it, which denotes date, rate, availability on the given date. 

For a villa to be available, all the stay nights for which client is going to stay, should be available. For eg Client wants to stay in a villa between 1-1-2021 to 5-1-2021, but 3-1-2021 is unavailable, the villa is unavailable for this stay.

But if someone wants to stay between 1-1-2021 to 3-1-2021 the villa is available as he/she will be checking out in the morning of 3-1-2021

A villa's total price can be calculated as the sum of the price of individual nights for which client is staying + 18% GST.

## Creating the tables.
- Create the required tables using db migration

## Write following APIs

- API to list villas which denotes average price per night and availability of the villa for entered dates. This API should also sort by price and availability depending upon query parameters
- API to calculate the total rate along with availability of a villa for entered dates

## Running the app

Simple hit run! You can edit the run command from the `.replit` file.

## Running commands

Start every command with `bundle exec` so that it runs in the context of the installed gems environment. The console pane will give you output from the server but you can run arbitrary command from the shell without stopping the server.

## Database

SQLite would work in development but we don't recommend running it in production. Instead look into using the built-in [Replit database](http://docs.replit.com/misc/database). Otherwise you are welcome to connect databases from your favorite provider. 

## Help

If you need help you might be able to find an answer on our [docs](https://docs.replit.com) page. Alternatively you can [ask in the community](https://replit.com/talk/ask). Feel free to report bugs [here](https://replit.com/bugs) and give us feedback [here](https://Replit/feedback).


