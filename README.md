<a name="readme-top"></a>

<!-- ABOUT THE PROJECT -->
## About The Project

Collabrative flashcards for all units in Edith Cowan Universities `U65 Computer Science` course, as well as both majors. See [Usage](#usage) for how to import and start using the flashcards. See [Contributing](#contributing) for how to contribute your own flashcards for any unit.

**Ensure you have the [Prerequisites](#prerequisites)**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- PREREQUISITES -->
## Prerequisites

1. Install [Anki Desktop](https://apps.ankiweb.net/), it is also recommended to create an [account](https://ankiweb.net/about)
2. Open Anki Desktop, under `Tools > Addons > Get Add-ons`, place `1788670778` in the code input and then click OK
   1. This will install the CrowdAnki JSON addon
3. DONE! See [Usage](#usage) or [Contributing](#contributing)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

To contribute your own flashcards, please fork the repo and create a pull request. 

1. [Fork](https://github.com/Computurtle/u65-notes/fork) the Project, and clone the fork to your desktop [`git clone forkURL.git`]
2. Create a new branch [`git checkout -b my-anki-cards`] - *Name it whatever*
3. In Anki, `File > CrowdAnki: Import from disk` and choose a deck within the folder you cloned
4. In Anki, `Add` a new flashcard, make as many as you want, ensure you are adding it to the correct deck
5. Once you have made your changes, `File > Export` and select `CrowdAnki JSON representation`
6. Include the deck you made changes to and ensure `Include media` and `Include tags` is checked
7. Commit your Changes [`git commit -m 'add: MAT1252'`] - *See [Commit Message Guide](#commit-message-guide)*
8. Push to the Branch [`git push origin my-anki-cards`] - *Or whatever you called your branch*
9. Open a [Pull Request](https://github.com/Computurtle/u65-notes/compare) and your done! Repeat 2-9 anytime you want add more cards

*If you don't want to contribute but simply want to use the flashcards, see [Usage](#usage)*

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- COMMIT MESSAGE GUIDE -->
## Commit Message Guide

When commiting please follow this guide, leave the pull request as the latest commit name 

'`add: UNIT1234`'

`add` = Added new cards </br>
`del` = Deleted old cards </br>
`fix` = Fixed old cards </br>

Commits can include multiple types of changes as well as multiple decks </br>
e.g. '`add/fix: MAT1252/CSI1101`'

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- USAGE EXAMPLES -->
## Usage

Want to import the flashcards into your Anki and start studying? Follow the steps below.

1. Using the terminal, `cd` to a folder you want to clone the repository to
2. Clone the repository [`git clone https://github.com/Computurtle/u65-notes.git`]
3. In Anki, `File > CrowdAnki: Import from disk` and select the folder for the unit you want to import
4. [`git pull`] the repository anytime you want the latest cards, and import any of the folders you wish

*If you find any issues with a flashcard, you can edit them locally, it would be appreciated if you let us know by submitting an [issue](https://github.com/Computurtle/u65-notes/issues)*

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/Computurtle/u65-notes.svg?style=for-the-badge
[contributors-url]: https://github.com/Computurtle/u65-notes/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Computurtle/u65-notes.svg?style=for-the-badge
[forks-url]: https://github.com/Computurtle/u65-notes/network/members
[stars-shield]: https://img.shields.io/github/stars/Computurtle/u65-notes.svg?style=for-the-badge
[stars-url]: https://github.com/Computurtle/u65-notes/stargazers
