# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Immad Arshad

Time spent: 6 hours spent in total

Link to project: https://glitch.com/edit/#!/notch-alluring-mandevilla

## Required Functionality

The following **required** functionality is complete:

* [ ] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [ ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [ ] Game buttons each light up and play a sound when clicked. 
* [ ] Computer plays back sequence of clues including sound and visual cue for each button
* [ ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [ ] User wins the game after guessing a complete pattern
* [ ] User loses the game after an incorrect guess

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

![](https://i.imgur.com/u0CV8Hz.gif)


## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
https://developer.mozilla.org/en-US/docs/Web/API/BaseAudioContext/createOscillator
https://www.w3schools.com/js/default.asp

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
The challenging thing was to understand what was the variables used for, such as "guessCounter" and "progress". 
Then I had to find out how many conditions (such as if/else) cases I needed to make to make this program work.

To find out what guess counter and progress did was I used console.log(guessCounter) and  console.log(progress). this showed me that guesscounter was 
how many choices i was choosing and progress was how many choices the program made. 
For me to find out how many conditions were to be made I had to write down and see how many ways would the program end.
Then I would need to keep track of my guessCounter and progress and see if they are working correctly. 
At times there were errors and incorrect outcomes I was getting so I had to retrack my logic in this program

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
The part when we had to make the sounds for this program using the frequencies and wavelength, my question is do
we have to know the coding for making the sounds? Understanding that part was confusing and I spent some time trying to 
understand the code.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
I would try to make something that would keep track of the time and the person who finishes the game the fastest holds the record. Another thing I would change is instead of making all 4 buttons
one type of shape, I would give every button its unique shape. 

## License

    Copyright [Immad Arshad]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.