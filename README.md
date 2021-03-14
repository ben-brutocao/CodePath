# Pre-work - _Memory Game_

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program.

Submitted by: Ben Brutocao

Time spent: 3 hours spent in total

Link to project: https://i.imgur.com/XBYIyHs.gif
## Required Functionality

The following **required** functionality is complete:

- [!] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
- [!] "Start" button toggles between "Start" and "Stop" when clicked.
- [!] Game buttons each light up and play a sound when clicked.
- [!] Computer plays back sequence of clues including sound and visual cue for each button
- [!] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess.
- [!] User wins the game after guessing a complete pattern
- [!] User loses the game after an incorrect guess

The following **optional** features are implemented:

- [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
- [!] Buttons use a pitch (frequency) other than the ones in the tutorial
- [ ] More than 4 functional game buttons
- [!] Playback speeds up on each turn
- [!] Computer picks a different pattern each time the game is played
- [ ] Player only loses after 3 mistakes (instead of on the first mistake)
- [ ] Game button appearance change goes beyond color (e.g. add an image)
- [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
- [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![https://i.imgur.com/XBYIyHs.gif)]
## Reflection Questions

1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
   
I used W3Schools for some basic JS notation that I did not remember. However, I have built JS games before, so I did not need to look many things up.
   

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words)

I made two fundamental changes to the game: I made it speed up as the player progresses, and made each run unique. Both of these were challenges, and I had to think for a while about how to accomplish the tasks. Many different ideas presented themselves, and I wrote multiple solutions to the unique set problem for about a half hour before I settled on simply remaking the list randomly each time.
For the time problem, I could not figure out how to make the pauses revert to their original length. I knew that I wanted to reiterate them, but I I could not find the correct place for them, and found error after error. However, by spending enough time with it and reading thoroughly all the code (even the part that was provided), I was able to locate the correct place for it.
These were the two main problems, and both were rewarding to solve on my own.


3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words)
 
Most of my questions regarding web-development are more business related, such as where it is cheapest to host websites and applications. I understand the theory and the creativity, but the practical side of tech is what I am most curious about.
For example, I can build a game, but I have no idea how to build an application that I could sell.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words)
   
If I had a few more hours, I would have definitely buffed up the cosmetics. I would most likely have changed the colors of the buttons to images, and different images on click. 
   But, on the more technical side, I would have instituted a log of past rounds, as well as success rate. Then, if enough people played, I could set an average and create levels for the game.
   Beyond that even, I would make minigames within the larger set. For example, having a little circle appear only for 2 seconds, and causing the player to lose if they don't click it in that time.
   

## License

    Copyright [YOUR NAME]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
