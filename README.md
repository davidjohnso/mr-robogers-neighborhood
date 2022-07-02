# Mr Roboger's Neighborhood

#### By David Johnson

## Technologies Used

* HTML
* CSS
* Bootstrap
* JavaScript

## Description

[Language Suggester](https://davidjohnso.github.io/mr-robogers-neighborhood/) is an web application that takes a number from the user and returns a list of values from 0 to the user's inputted number with the following substitutions made within the returned list:

  * For numbers that contain a 1, all digits are replaced with "Beep!"
    * For example, all digits of the number *109*, *11*, or *1* would be replaced with *"Beep!"*
  * For numbers that contain a 2, all digits are replaced with "Boop!"
    * For example, all digits of the number *2*, *24*, or *2099* would be replaced with *"Boop!"*
  * For numbers that contain a 3, all digits are replaced with "Won't you be my neighbor?"
    * For example, all digits of the number *39*, *3*, or *8763* would be replaced with *"Won't you be my neighbor?"*

## Setup/Installation Requirements

* Navigate to my Github: https://github.com/davidjohnso/mr-robogers-neighborhood.
* Clone the repository to your desktop.
* Navigate to the top level directory.
* Open index.html in your browser.

## Known Bugs

*  No known bugs currently.

## License

This project is licensed under the terms of the [MIT license](LICENSE).

## TDD (Test Driven Development)

Describe: beepBoop()

Test: "It should return an array of numbers from 0 to the user's inputted number"
Code: beepBoop(5);
Expected Output: [0, 1, 2, 3, 4, 5]

## Copyright (c) 2022 David Johnson