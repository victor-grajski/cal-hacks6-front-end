<h1 align="center">
<img
		width="250"
		alt="Tinder Clone - React Native"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/tinder-clone-logo.gif">
</h1>
<h3 align="center">
	Tinder Clone - React Native
</h3>

<p align="center">
	<img alt="Last Commit" src="https://img.shields.io/github/last-commit/stevenpersia/tinder-react-native.svg?style=flat-square">
	<img alt="Licence" src="https://img.shields.io/github/license/stevenpersia/tinder-react-native.svg?style=flat-square">
	<img alt="Star" src="https://img.shields.io/badge/you%20like%20%3F-STAR%20ME-blue.svg?style=flat-square">
</p>

<p align="center">
	<img src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/tinderclone-preview.gif" width="300">
</p>


## Overview

**Perfect to start an Tinder Clone app.** 4 screens are availables : Explore, Matches, Messages and Profile. You'll find some components like Card Component to pass props and variant. No frameworks UI like Bootstrap or Material UI are used.

More features will be added to the project in the future.

This project was inspired by this [amazing Kishore's work on Dribbble](https://dribbble.com/shots/5631075-Dating-App-Sketch-Freebie-Day-334-365-Project365). Feel free to follow this guy because he does great stuff.


## Screenshots

<img
		width="210"
		alt="Capture 1"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-1.png">
<img
		width="210"
		alt="Capture 2"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-2.png">
<img
		width="210"
		alt="Capture 3"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-3.png">
<img
		width="210"
		alt="Capture 4"
		src="https://github.com/stevenpersia/tinder-react-native/blob/master/preview/capture-4.png">


## Installation and usage

Be sure, you have installed all dependencies and applications to run React Native project on your computer (React Native CLI Quickstart): [Getting Started with React Native](https://facebook.github.io/react-native/docs/getting-started).

This project works fine for iOS but in Android version there are serious UI problems because I've only worked on iOS.


### Running the project

Clone this repository :

```
git clone https://github.com/victor-grajski/cal-hacks6-front-end.git
cd cal-hacks6-front-end
```

Install packages :

```
npm install
```

When installation is complete, run with version of your choice :

```bash
react-native run-ios --simulator="iPhone 11"
# or
react-native run-android
```

To hot reload:
* Enable keyboard shortcuts in the Simulator by going to Hardware > Keyboard and Checking `Enable Keyboard Shortcuts to Device`
* Open dev tools with `⌘D` and tap `Enable Hot Reloading`
* Edit any file and save!

## Props

### CardItem

| Name           | Type     | Required | Description                                               | Example                                             |
| -------------- | -------- | -------- | --------------------------------------------------------- | --------------------------------------------------- |
| `image`        | string   | Yes      | Picture of member.                                        | `image="https://..."`                               |
| `name`         | string   | Yes      | Name of member.                                           | `name="John Doe"`                                   |
| `description`  | string   | Yes      | Description of member.                                    | `description="Full-time Traveller. Globe Trotter."` |
| `matches`      | string   | Yes      | Match percentage.                                         | `matches="95"`                                      |
| `actions`      | boolean  | No       | Display actions buttons (Like, Dislike, ...).             | `actions`                                           |
| `onPressLeft`  | function | No       | Swipe card to left.                                       | `onPressLeft={() => this.swiper.swipeLeft()}`       |
| `onPressRight` | function | No       | Swipe card to right.                                      | `onPressRight={() => this.swiper.swipeRight()}`     |
| `status`       | string   | No       | Display online or offline badge (`Online` and `Offline`). | `status="Online"`                                   |
| `variant`      | boolean  | No       | Display another style of card (used for Matches screen).  | `variant`                                           |

### Message

| Name          | Type   | Required | Description             | Example                                                                                      |
| ------------- | ------ | -------- | ----------------------- | -------------------------------------------------------------------------------------------- |
| `image`       | string | Yes      | Picture of member.      | `image="https://..."`                                                                        |
| `name`        | string | Yes      | Name of member.         | `name="John Doe"`                                                                            |
| `lastMessage` | string | Yes      | Last message of member. | `lastMessage="You want order in Gotham. Batman must take off his mask and turn himself in."` |


### ProfileItem

| Name       | Type   | Required | Description                 | Example                                    |
| ---------- | ------ | -------- | --------------------------- | ------------------------------------------ |
| `name`     | string | Yes      | Name of member.             | `name="John Doe"`                          |
| `matches`  | string | Yes      | Match percentage.           | `matches="95"`                             |
| `age`      | string | No       | Age of member.              | `age="25"`                                 |
| `location` | string | No       | Location of member.         | `location="Paris, France"`                 |
| `info1`    | string | No       | More information of member. | `info1="Straight, Single"`                 |
| `info2`    | string | No       | More information of member. | `info2="Tea Totaller & Loves Photography"` |
| `info3`    | string | No       | More information of member. | `info3="Beaches, Mountain & Coffee"`       |
| `info4`    | string | No       | More information of member. | `info4="Last seen: 23h ago"`               |


## Star, Fork, Clone & Contribute

Feel free to contribute on this repository. If my work helps you, please give me back with a star. This means a lot to me and keeps me going!

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<table>
  <tr>
<td align="center"><a href="http://Skibudsapp.com"><img src="https://avatars3.githubusercontent.com/u/25047763?v=4" width="100px;" alt="Stephen Phillips"/><br /><sub><b>Stephen Phillips</b></sub></a><br /><a href="#question-Sbphillips19" title="Answering Questions">💬</a></td>
<td align="center"><a href="https://github.com/anand9"><img src="https://avatars3.githubusercontent.com/u/638590?v=4" width="100px;" alt="Anand Vasudevan "/><br /><sub><b>Anand Vasudevan </b></sub></a><br /><a href="https://github.com/stevenpersia/tinder-react-native/commits?author=anand9" title="Code">💻</a></td>
  </tr>
</table>

<!-- ALL-CONTRIBUTORS-LIST:END -->
