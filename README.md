# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Michael Chan**

Time spent: **2** hours spent in total

Link to project: (https://glitch.com/edit/#!/paper-wooded-badger)

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

* [ ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [ ] Playback speeds up on each turn
* [ ] Computer picks a different pattern each time the game is played
* [ ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:
![http://g.recordit.co/jwvdLNEofI.gif](your-link-here)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
[None]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
[A weird challenge I had was with the progress counter, I was using it to signal whether the game was finished, but the equals symbol wasn't working as intended at first. Using what I learned from other programming languages, I wanted to compare the progress counter with the size of the pattern to check whether the pattern was completely finished, but then I learned the size of the array for the line I put was undefined(pattern.size). For the default version of the game the size of the pattern. Unrelated to the code iself, but I also had an issue using glitch.com creating an account (website would not load) and exporting it to github, taking a long time to find the pull request. Most of the coding went into the if statements that we had to fill in ourselves, where the difficulties were the same if I were coding normally. What was new was that many different variables were already given to us and initialized, so it was up to me to manipulate them to finish the game which I found interesting. I went back to make sure of the purpose for the GuessCounter and Progress, to understand what I needed to do to create the outcomes desired when running the game.]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
[One thing that I was always curious about web development was the use of art when creating a website or app. For this project, we used colors alraedy known and applied them to the buttons and background, so I wanted to know the difficulties of implementing your own art into your work and its importance. I know that catching a person's attention quickly is a huge deal to those running websites and I believe that creating your own design would be imperative to achieve that goal. Also, I wondered how projects are coded so they can be viewed on different browsers and devices. One would most likely have to code a certain way to achieve cross-platform access or all devices/platforms would have to support the same plugins/functions.]

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
[I really rushed to finish this project, but if I had more time, I would have made the game more customizable for the user. The option
that I wanted to implement the most was a change in difficulty, to give the player options for easy, medium, and hard in which each would have different amounts of time to enter gusses or varying times the buttons in the pattern are lit. There were many snippets of code given to us already for this project, and most of the functions were given as well. If given more time I would have experimented more with buttons to see what I could have done with them, possibly customize tone frequencies and put different appearances for the game. The most important implementation that I wanted to do was randomize the pattern each game by randomizing the values in the array and setting customizations to change the number of buttons in a pattern as well.]



## License

    Copyright [Michael Chan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
