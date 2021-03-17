# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: **Tanzila Morshed**

Time spent: **5** hours spent in total

Link to project: https://glitch.com/~code-path-site

## Required Functionality

The following **required** functionality is complete:

* [ x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x ] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x ] Game buttons each light up and play a sound when clicked. 
* [x ] Computer plays back sequence of clues including sound and visual cue for each button
* [x ] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x ] User wins the game after guessing a complete pattern
* [x ] User loses the game after an incorrect guess

The following **optional** features are implemented:

* [x ] Any HTML page elements (including game buttons) has been styled differently than in the tutorial
* [ ] Buttons use a pitch (frequency) other than the ones in the tutorial
* [ ] More than 4 functional game buttons
* [x ] Playback speeds up on each turn
* [x ] Computer picks a different pattern each time the game is played
* [x ] Player only loses after 3 mistakes (instead of on the first mistake)
* [ ] Game button appearance change goes beyond color (e.g. add an image)
* [ ] Game button sound is more complex than a single tone (e.g. an audio file, a chord, a sequence of multiple tones)
* [ ] User has a limited amount of time to enter their guess on each turn

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app!

## Video Walkthrough

Here's a walkthrough of implemented user stories:

1: ![](https://i.imgur.com/qaGSV8t.gif)
2: ![](https://i.imgur.com/MuT7NIo.gif)
3: ![](https://i.imgur.com/N9t5RrW.gif)
4: ![](https://i.imgur.com/LOoufoT.gif)
5: ![](https://i.imgur.com/GdPIU7j.gif)





## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here.
 
[N/A (everything used was listed on the prework tutorial)]

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 

[A challenge that I encountered while creating this submission actually occurred early on, with trying to get the start and stop buttons to appear and disappear correctly. To be completely transparent, for the first 10 minutes that this bug was occurring, I had no idea what was going wrong. I was checking the code on the tutorial and finding that the code I was using matched exactly. I then realized that I had misunderstood some of the ordering of the function calls, so after fixing this, I tried again, finding again that the switch between start and stop was not occurring correctly. Noting that there was probably a syntax-type error that I was missing, I deleted the function calls and typed them again, making sure to note that the ID’s of the buttons were listed correctly and that I was calling the correct aspects of the HTML page in the correct order. I repeated this with the stop button and checked again that I had called the buttons hiding in the correct order. After this, the button worked as it was supposed to, which was relieving. This was a pretty small bug, but for a bug that I could not find as easily, I would repeat these beginning steps, making sure to add in calls to console.log() to debug what exactly is going wrong, and make small changes at a time to pinpoint the changes in my code. ]

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 

[After completing my submission, I have questions about the connection between what the user does and how that manifests itself in code. For example, we did some simple user input work using buttons, but what do more sophisticated interactions look like? Additionally, while this was not exactly touched on in this submission specifically, I generally have more questions about the backend side of things outside a simple memory game. For “real” and more sophisticated websites, where does user data go, and how is it accessed? How does development work on a larger scale? These are relatively vague questions, but I am genuinely curious about learning more about how web development works in the real world. ]


4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 

[If I had a few more hours to work on this project, I would probably try to do more with the front-end side of things to make it more interesting. I would also try to implement more of the optional features that were mentioned, especially the timer on the user’s attempts and adding different audio files than just a pitch playing. I think changing the audio from the default pitch combined with changing the game buttons into pictures could make an easy branded game for specific companies, so it would be cool to look down that path. In terms of the buttons itself, I think it could be interesting if they moved as well as lighting up and playing sounds, to add another element to the game. However, I’m not exactly sure how that would be executed, and I think it would take many more underlying elements to be able to achieve this.  ]




## License

    Copyright [Tanzila Morshed]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
