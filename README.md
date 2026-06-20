# WEB102 Prework - Sea Monster Crowdfunding

Submitted by: **Vu Nguyen**

**Sea Monster Crowdfunding** is a website for the company Sea Monster Crowdfunding that displays information about the games they have funded.

Time spent: **3** hours spent in total

## Required Features

The following **required** functionality is completed:

* [x] The introduction section explains the background of the company and how many games remain unfunded.
* [x] The Stats section includes information about the total contributions and dollars raised as well as the top two most funded games.
* [x] The Our Games section initially displays all games funded by Sea Monster Crowdfunding
* [x] The Our Games section has three buttons that allow the user to display only unfunded games, only funded games, or all games.

The following **optional** features are implemented:

* [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

Here's a walkthrough of implemented features:

[Video Walkthrough](https://imgur.com/a/VHjdSAe)

<!-- Replace this with whatever GIF tool you used! -->
GIF created with LICEcap 
<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

This prework builds a dynamic crowdfunding dashboard using vanilla JavaScript. The main challenges completed in `index.js` include:

- **Challenge 3:** Render each game as a card in the games container using DOM manipulation, `for` loops, and template literals.
- **Challenge 4:** Compute and display summary stats (total contributions, amount raised, number of games) using `reduce()` and `toLocaleString()`.
- **Challenge 5:** Filter games by funding status with `filter()` and wire up the Unfunded, Funded, and All buttons with event listeners.
- **Challenge 6:** Add a company description with the total raised, number of games, and unfunded count using template literals and the ternary operator.
- **Challenge 7:** Sort games by pledged amount and display the top two funded games using `sort()`, destructuring, and the spread operator.

Describe any challenges encountered while building the app.

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
