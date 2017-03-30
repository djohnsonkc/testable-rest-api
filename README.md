
# Creating a testable REST API using Node.js, express, Mocha, and Chai
###### Created: March 23, 2016
###### Author: Dywayne Johnson - Full-Stack Developer of mobile-optimized web apps, hybrid native apps, APIs, and databases
###### Email: djohnsonkc@gmail.com

### Details
--------------

Based on the great work explained this article:
##### https://scotch.io/tutorials/test-a-node-restful-api-with-mocha-and-chai
##### Source: https://github.com/samuxyz/bookstore

#### Key alterations:

Rather than return the native Mongoose responses, I prefer to package them differently so that 
I can optimize the responses with proper HTTP status code as well as conceal the implementation. 
I also will be continuing to tweak this project to tailor it more to other preferences as well as 
extend the MongoDB queries to demonstrate some other features of Mongoose.

#### Start the API
> $ npm start

#### Test the API
> $ npm test
