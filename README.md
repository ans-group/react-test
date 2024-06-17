# ans/blockchain

**This project will depend on your ability to fulfil the task requirements. Any potential design skills are a bonus, but usability, performance and security will be considered.**

## Introduction

This project provides a starting point for creating an app that retrieves data from the blockchain API to fetch cryptocurrency information.

## Project Requirements

We require this project to be completed in React. You are welcome to use Remix or NextJS. **However, using those frameworks has no effect on the outcome. ** You are more than welcome to use utility frameworks like TailwindCSS.

## Task Requirements

Create an app that allows users to search for a cryptocurrency and convert currencies. A RESTful API is available at [Blockchain](https://blockchain.info/ticker)

The app should have two views: one for displaying the currencies returned and one for converting an inputted amount of a particular currency. There should be a way to navigate between the two views.

We recommend that you spend no more than one hour on this challenge, we are more interested in how you approach the task than spending lots of time on it.


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
