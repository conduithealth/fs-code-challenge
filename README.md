# fs-code-challenge

## Summary

In this at-home challenge, you will build an application according to some requirements below. This exercise will expose you to some very simplified versions of use cases we have solved already, and should give you an idea of our domain. 

For context, our current stack at Conduit Health uses Python (FastAPI) and Typescript (React / Remix). While showing proficiency in our tech is helpful, it's not required, and you are free to use whatever language/framework you are most comfortable building quickly with.

We recommend spending 3-4 hours on this. Build out what you can in that timeframe and take note of what you'd add if you had more time.

Once your solution is submitted, we will review internally and schedule a follow up for further discussion. 

Thanks for taking the time to work on this, and we look forward to seeing your app!

## Instructions

1. Clone this repo locally
2. Build an app that meets the requirements in Requirements section (or as many requirements as you can in the recommended time)
   * Use the sample data in ./sample-data.json as your db
   * Create an API that returns the sample data and simulates a loading time of 1.5 seconds of pretend latency
   * Create a front end with a single page that can query the API and show a list and count of applicable products
3. Create a new private repository on your github
4. Push your work up to your local clone, committing as you go
5. Add the following to your README:
   * Instructions on how to run your application / interact with your API (include documentation for your API that you would want if you were consuming it)
   * What technologies you chose to use and why
   * Anything you wanted to do but ran out of time for
   * Anything else relevant that we should know
6. Add the github user(s) named when you received this challenge as viewers
7. Reply in an email when your submission is ready for us to look over


## The Problem

> As a user, I want to see a list of DME products available to order, filtered by insurance eligibility, supplier availability, and category.

## Requirements 

```
Scenario: The application displays a list of all available products
  As a user
  When I open the application
  The full, unfiltered list of products is returned
  The count of products is shown
```

```
Scenario: The list of products can be filtered by Payors in network
  As a user
  When I filter the list of products by payor
  The relevant list of products is returned
  The count of filtered products is shown
```

```
Scenario: The list of products can be filtered by available Supplier
  As a user
  When I filter the list of products by supplier
  The relevant list of products is returned
  The count of filtered products is shown
```

```
Scenario: The list of products can be filtered by category
  As a user
  When I filter the list of products by category
  The relevant list of products is returned
  The count of filtered products is shown
```

```
Scenario: The list of products can be searched
  As a user
  When I enter a search query
  The relevant list of products is returned
  The count of filtered products is shown
```
