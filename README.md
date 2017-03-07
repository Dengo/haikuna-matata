[![Build Status](https://travis-ci.org/hollabaq86/haikuna-matata.svg?branch=master)](https://travis-ci.org/hollabaq86/haikuna-matata)

# Haikuna-Matata
---
## A Machine Learning Haiku Generator

### A project developed by Holly Stotelmyer (@hollabaq86), Noah Guy (@NoahRGuy), Dennis Marchetti (@dmarchet) and Joan Petersohn (@jepetersohn)


## Description

Haikuna-Matata generates completely original, correctly formatted haiku based on user input. A user types a word into the console when running the program, and the program will return a 5/7/5 style haiku built around the user's input. Given no user input, the haiku generated will be centered around a randomly generated word or pair of words. Users are then asked to rate the coherence of each line of the haiku. If a line is up-voted, the frequency of those word pairings will increase in the database. If a line is down-voted, the frequency of those word pairings will decrease in the database. Overtime, this will train the generator to create more coherent haiku.

![image](https://cloud.githubusercontent.com/assets/19498387/23668761/a18b77ca-0327-11e7-8df1-d7bb99bbc37d.png)

![image](https://cloud.githubusercontent.com/assets/19498387/23668796/b9c1b476-0327-11e7-8935-d00d086f847d.png)

Basic Haiku Requirements
---
All Haiku are defined by the following structure
* Each haiku has 3 lines.
* Each haiku follows the following syllable construction for each line
* 5 syllables for the first line
* 7 syllables for the second line
* 5 syllables for the third line

Intermediate Haiku Requirements
---
All Haikus must
* Be centered around a user provided word, or given no user input, centered around a randomly generated word
* Have no line ending in a preposition

Advanced Haiku Requirements
---
Stretch Goals for the machine to learn
* Haikus must make sense.
* All haikus will follow proper grammatical structure.


