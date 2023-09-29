# Web Development Project 2 - Indoor Bouldering Quiz

Submitted by: Tashi Sherpa

This web app: Indoor Bouldering Quiz

Time spent: 6 hours spent in total

## Required Features

The following **required** functionality is completed:

- [x] **The title of the card set and some information about it, such as a short description and the total number of cards are displayed**
- [x] **A single card at a time is displayed, only showing one of the components of the information pair**
- [x] **A list of card pairs is created**
- [x] **Clicking on the card shows the corresponding component of the information pair**
- [x] **Clicking the next button displays a random new card**

The following **optional** features are implemented:

- [x] Cards contains images in addition to or in place of text
- [x] Cards have different visual styles such as color based on their category
  - [x] 'Easy' cards are green, Medium cards are yellow, and 'Hard' cards are red.

The following **additional** features are implemented:

- [x] Included blurred background photo of indoor bouldering!
- [x] Card flip transition.

## Video Walkthrough

Here's a walkthrough of implemented required features:

![](https://github.com/TSherpa10/project2-web102/blob/main/codepath_project2.gif)

<!-- Replace this with whatever GIF tool you used! -->

GIF created with Kap

<!-- Recommended tools:
[Kap](https://getkap.co/) for macOS
[ScreenToGif](https://www.screentogif.com/) for Windows
[peek](https://github.com/phw/peek) for Linux. -->

## Notes

I struggled a bit on the representation of the data (8 Cards). To alleviate this,
I represented each Card as a card component with passed in props, and made a list of Card components.

I also struggled with the animation (transition) aspect, but I had to fiddle with the CSS nesting and had help from Codepath Office Hours, resulting in a clean finished product.

## License

    Copyright [2023] [Tashi Sherpa]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
