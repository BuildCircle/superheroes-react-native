# superheroes-react-native

Superheroes and villains are always battling it out, but how do we know who wins? In this test we will create a single page application to find out.

The superhero and villain characters along with their stats are stored in a public json file stored in AWS S3 - https://s3.eu-west-2.amazonaws.com/build-circle/characters.json

During a battle the character with the highest score wins.

We expect the solution to be simple, readable, and to be supported by good unit tests (reliable, fast, and asserting behaviour).

## Setup
Create a new project using the create react-native app cli with the android or IOS simulator for testing

## Hero and villain name input
We need a way of taking in a hero name and a villain name as inputs, and a battle button to trigger the fight!

## Triggering the battle
When the battle button is clicked, we need to load the characters JSON file and find the characters by their name. We can then compare the scores of each character, the winner has the higher score. We should show the winner on the page after the battle is over.

## Weaknesses
Some heroes have weaknesses when matched against specific villians, taking this into account we wan't to reduce a heroes score by 1 when they are matched with a weakness.
