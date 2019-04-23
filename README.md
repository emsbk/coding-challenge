# Coding Challenge

You need to build a simple system so that people will be able to purchase events online.

The sales team have some new promotions they want to offer so we need to introduce a mechanism for applying discounts to orders.

Promotions like this can and will change over time so you need the solution to be flexible.

### Events

These are the events you are offering in your app

| Events        | Cost  |
| ------------- | ----- |
| Kids Party    | \$220 |
| Wine Tour     | \$440 |
| Team Building | \$800 |
| Picnic        | \$110 |

### Promotions

| Events                 | Rules                                 |
| ---------------------- | ------------------------------------- |
| Any                    | Buy 5, Get 20% off the 5th experience |
| Team Buildings         | Buy 2 for \$1500                      |
| Wine Tours and Picnics | Buy 4, ONLY Pay for 3                 |
| Picnics                | Buy 2, get 1 free                     |

### Examples

Based on both discounts applied, the following examples should be valid:

- Random Pty Ltd purchased 2 Wine Tour packages to Yarra Valley and Macedon Ranges, based on the defined discounts the total should be \$880.00
  discounts

- Not So Random Pty Ltd purchased 4 Wine Tour packages to Yarra Valley, based on the defined discounts the total should be \$1320.00

### What we want from you

Provide a means of defining and applying various discounts to the cost of customers purchasing experiences.

Setup your project by creating a new react app using TypeScript.

`npx create-react-app coding-challenge --typescript`

- You should focus on your area of strength and interest. You have the freedom to complete the challenge your way.
- You should provide a copy of your code and include a readme detailing how to run your code as well as how you approached the problem, ideally, the code should be hosted in an online code repository.
- Please supply us with the URL to your solution as part of your application - you may choose to host your solution however you like, so long as we are able to access it.
- We need to be able to build and run your code ourselves.

