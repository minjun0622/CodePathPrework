# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Minjun Seo**

Time spent: **6** hours spent in total

Link to project: (insert your link here, should start with https://oasis-fascinated-thorn.glitch.me/)

## Required Functionality

The following **required** functionality is complete:

* [X] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [X] "Start" button toggles between "Start" and "Stop" when clicked. 
* [X] Game buttons each light up and play a sound when clicked. 
* [X] Computer plays back sequence of clues including sound and visual cue for each button
* [X] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [X] User wins the game after guessing a complete pattern
* [X] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [X] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [X] Buttons use a pitch (frequency) other than the ones in the tutorial
* [X] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [X] Computer picks a different pattern each time the game is played
* [X] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [X] List anything else that you can get done to improve the app!
- Set a boolean called music and if that is true, the pattern is set to the tone of Mary Had a Little Lamb instead of generating a random pattern.

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:

<img src="http://g.recordit.co/J5LMFayNQD.gif" width=400><br>
<img src="http://g.recordit.co/WAJmpjMpXH.gif" width=400><br>
<img src="http://g.recordit.co/KDfFKBHAcC.gif" width=400><br>

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
- https://www.w3schools.com/
- https://www.stackoverflow.com/

This website helped me understand the syntax in creating loops and implementing the logic behind the skeleton code in the script.js file.

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The challenge in creating the submission was in first, the implementation of the guess function where I had trouble with understanding the syntax regarding the if statements, and general syntax for the to build the method. I was able to overcome this by looking up examples through a source cited above, w3schools.com to help figure it out. 

The next difficulty, which to me, was the most difficult one, was adding different patterns everytime. Since I am well versed in Java and Python, my first thought process was to iterate through the list with a for loop and change each value inside the array doing patterns[i] = a random number that I got. Instead, I was able to find out through Stack Overflow that to add to a list in Javascript, there is a push method that would push to the end of the list. Therefore, I was able to overcome this part of the additional feature.

In general, most of my difficulties came from implementing additional features as shown in the checklist and in the video. I attempted to implement the extra chance feature to enable the player to have more than one guess. I first defined a global variable called forgiveness and tried to decrement it within an if statement inside the guess method. However, I was able to see that the game did stop after 3 wrong tries. However, it would freeze if I guessed the wrong thing. This was able to be averted by writing playClueSequence() right after the decrementation of the variable to make the website play the same pattern again. 

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
After completing my prework, I became curious into how this work can be split between the frontend and backend engineers. I have experience with frontend and therefore, I understood that that part dealt more into the looks side of the website, dealing with the shape and layout of the buttons and words. If this was a website that I was building from scratch without Glitch, and if I were to be a backend engineer, what would my work look like? Does full-stack mean they would deal with both backend and frontend?

Therefore, I would like to look into the process of how the website gets published with a link and gets connected with a server, something that Glitch is doing automatically. 

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
Some of the things that I would further implement, given more time, is adding a buttong right next to the start/end button that would change the value of the music variable that I have in the code. The music variable, when true, sets the pattern to the notes of Mary Had a Little Lamb. Since the frequency of my buttons represent music notes from C, D, E, F, G, A, this would also be able to be expanded by allowing the users to have the choice between playing a music memory game along the tunes of a specific song they would like. 

Following along my idea, there could be a scoreboard in which globally, it gives points for getting the buttons right in the correct order. Then, the user would put their user name to create competition among users in the website. 


## Interview Recording URL Link

[My 5-minute Interview Recording](your-link-here)


## License

    Copyright Minjun Seo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
