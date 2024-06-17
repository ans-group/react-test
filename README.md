# ans/blockchain

**This project will be based primarily on your ability to fulfill the task requirements. Any potential design skills are a bonus, but usability, performance and security will be taken into account.**

## Introduction

This project provides a starting point which will allow you to create an app that retrieves the data from the blockchain api to fetch cryptocurrency information.

## Project Requirements

We require this project to be completed in React. You are welcome to utilise Remix or NextJS. **However using those frameworks has no effect on the outcome**. You are more than welcome to use utility frameworks like TailwindCSS.

## Task Requirements

Create an app that allows the users to search for a cryptocurrency, and allows them to convert the currencies. A RESTful API is available at [Blockchain](https://blockchain.info/ticker)

The app should have two views. One for displaying the currencies returned and one for converting an inputted amount of a particular currency. There should be a way of navigating/switching between the two views.


### User Stories

| As a <type of user>       | I want to <perform some task>                        | so that I can <achieve some goal>                                             |
|---------------------------|------------------------------------------------------|-------------------------------------------------------------------------------|
| End User                  | View a list of currencies                            | See the most recent market prices for each currency                           |
| End User                  | Convert an amount from one currency to another       | Understand the value of a given amount in a different currency                |
| End User                  | Navigate between the list view and conversion view   | Easily switch between viewing market prices and converting currency amounts   |

### Acceptance Criteria

#### List View

| GIVEN                       | WHEN                   | THEN                                                                                  |
|-----------------------------|------------------------|---------------------------------------------------------------------------------------|
| I am on the list view page  | The page loads         | I can see a list of available currencies                                               |
| ^                           | ^                      | Each currency shows the currency code                                                  |
| ^                           | ^                      | Each currency shows the most recent market price (last)                                |
| ^                           | ^                      | The market price is displayed with the currency symbol pre-pended                      |
| ^                           | I click on 'Convert'   | I am redirected to the conversion view                                                 |

#### Conversion View

| GIVEN                           | WHEN                          | THEN                                                                                  |
|---------------------------------|-------------------------------|---------------------------------------------------------------------------------------|
| I am on the conversion view page| The page loads                | I can see a form to select a currency and enter an amount                              |
| ^                               | I select a currency and enter an amount | I can see the converted value in a different currency                                   |
| ^                               | ^                             | The conversion result is displayed in a format that makes it easy to understand that “A amount of B is equal to X amount of Y” |
| ^                               | I click on 'Back to List'     | I am redirected to the list view                                                      |