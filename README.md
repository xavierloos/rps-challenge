# RPS Challenge

## Screenshots
<img src="public/img/Welcome to RPS.png" width="45%"> <img src="public/img/Single player enter name.png" width="45%">
<img src="public/img/Single player choose card.png" width="45%"> <img src="public/img/Multiplayer enter names.png" width="45%">
<img src="public/img/Multiplayer Player 1 chooses card.png" width="45%"> <img src="public/img/Multiplayer Player 2 choose card.png" width="45%">

## Instructions

- Feel free to use google, your notes, books, etc. but work on your own
- If you refer to the solution of another coach or student, please put a link to that in your README
- If you have a partial solution, **still check in a partial solution**
- You must submit a pull request to this repo with your code by 9am Monday morning

## Task

Knowing how to build web applications is getting us almost there as web developers!

The Makers Academy Marketing Array ( **MAMA** ) have asked us to provide a game for them. Their daily grind is pretty tough and they need time to steam a little.

Your task is to provide a _Rock, Paper, Scissors_ game for them so they can play on the web with the following user stories:

```
As a marketeer
So that I can see my name in lights
I would like to register my name before playing an online game

As a marketeer
So that I can enjoy myself away from the daily grind
I would like to be able to play rock/paper/scissors
```

Hints on functionality

:ballot_box_with_check: the marketeer should be able to enter their name before the game

:ballot_box_with_check: the marketeer will be presented the choices (rock, paper and scissors)

:ballot_box_with_check: the marketeer can choose one option

:ballot_box_with_check: the game will choose a random option

:ballot_box_with_check: a winner will be declared

As usual please start by

:ballot_box_with_check: Forking this repo

:ballot_box_with_check: TEST driving development of your app

## Bonus level 1: Multiplayer

:ballot_box_with_check: Change the game so that two marketeers can play against each other ( \_yes there are two of them\* ).

## Bonus level 2: Rock, Paper, Scissors, Spock, Lizard

Use the _special_ rules ( _you can find them here http://en.wikipedia.org/wiki/Rock-paper-scissors-lizard-Spock_ )

## Basic Rules

:ballot_box_with_check: Rock beats Scissors

:ballot_box_with_check: Scissors beats Paper

:ballot_box_with_check: Paper beats Rock

In code review we'll be hoping to see:

- All tests passing

- High [Test coverage](https://github.com/makersacademy/course/blob/master/pills/test_coverage.md) (>95% is good)
- The code is elegant: every class has a clear responsibility, methods are short etc.

Reviewers will potentially be using this [code review rubric](docs/review.md). Referring to this rubric in advance may make the challenge somewhat easier. You should be the judge of how much challenge you want this at this moment.

## Notes on test coverage

Please ensure you have the following **AT THE TOP** of your spec_helper.rb in order to have test coverage stats generated
on your pull request:

```ruby
require 'simplecov'
require 'simplecov-console'

SimpleCov.formatter = SimpleCov::Formatter::MultiFormatter.new([
  SimpleCov::Formatter::Console,
  # Want a nice code coverage website? Uncomment this next line!
  # SimpleCov::Formatter::HTMLFormatter
])
SimpleCov.start
```

You can see your test coverage when you run your tests. If you want this in a graphical form, uncomment the `HTMLFormatter` line and see what happens!
