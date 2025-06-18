

# Web Development Project 2 - Flashcards App

Submitted by: **Prashant Panta**

This web app: displays an interactive flashcard learning experience that shows randomized cards from a predefined set. Each flashcard contains a trivia question, and clicking flips the card to reveal the answer. The app helps users study concepts or facts in a dynamic and engaging way.

Time spent: 6 hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] **The app displays the title of the card set, a short description, and the total number of cards**

  * [x] Title of card set is displayed
  * [x] A short description of the card set is displayed
  * [x] A list of card pairs is created
  * [x] The total number of cards in the set is displayed
  * [x] Card set is represented as a list of card pairs (an array of dictionaries where each dictionary contains the question and answer is perfectly fine)
* [x] **A single card at a time is displayed**

  * [x] Only one half of the information pair is displayed at a time
* [x] **Clicking on the card flips the card over, showing the corresponding component of the information pair**

  * [x] Clicking on a card flips it over, showing the back with corresponding information
  * [x] Clicking on a flipped card again flips it back, showing the front
* [x] **Clicking on the next button displays a random new card**

The following **optional** features are implemented:

* [ ] Cards contain images in addition to or in place of text

  * [ ] Some or all cards have images in place of or in addition to text
* [ ] Cards have different visual styles such as color based on their category

The following **additional** features are implemented:

* [x] A "Previous" button is implemented to allow stepping back through cards
* [x] Clean, responsive layout with centered card design and styled buttons
* [x] Simple state logic using `useState` to track current card and flipped state

## Video Walkthrough

Here's a walkthrough of implemented required features:

<img src='https://imgur.com/a/YMzU2vZ' title='Video Walkthrough' width='' alt='Video Walkthrough' /> 


GIF created with LiceCap and Imgur.

<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

The main challenge was getting the randomization to feel smooth without repeating the same card too frequently. I also spent time adjusting CSS to ensure all cards and buttons remained centered and responsive.

## License


Copyright 2025 Prashant Panta

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.



