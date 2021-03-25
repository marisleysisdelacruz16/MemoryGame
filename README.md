# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Marisleysis De La Cruz

Time spent: 4 hours spent in total

Link to project: https://glitch.com/edit/#!/dawn-wooden-bandana

## Required Functionality

The following **required** functionality is complete:

[*] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
[*] "Start" button toggles between "Start" and "Stop" when clicked. 
[*] Game buttons each light up and play a sound when clicked. 
[*] Computer plays back sequence of clues including sound and visual cue for each button
[*] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
[*] User wins the game after guessing a complete pattern
[*] User loses the game after an incorrect guess

The following **optional** features are implemented:

[*] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
[*] Buttons use a pitch (frequency) other than the ones in the tutorial
[*] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
[*] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!
- Different pattern than the one in the tutorial

## Video Walkthrough

Here's a walkthrough of implemented user stories:

![](https://i.imgur.com/mBTdOxJ.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
In creating this submission, I encountered a problem with my buttons because they weren't turning back to their original color
after holding them down. I figured out that the problem was with the syntax because I didn't make
the buttons active AND give it the property of lit in the .css file. Another challenge I encountered was making the game
restart after having one wrong guess, but I was able to figure it out through debugging. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
One question I have is how would I go about creating this game so that it is mobile-friendly and accessible
through a tablet as well, not just a computer? Another question I have is what is the 
main platform used for web-design? How do you know when you're truly done with a project/website
since there is always something you can add to it?

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
If I had a few more hours to work on this project, I would add the feature of having the computer
pick a different pattern each time the game is played. I would also include background music aside from the 
tones of the buttons. Another feature I would've liked to implement is the playback speed up on each turn.



## License

    Copyright [Marisleysis De La Cruz]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.