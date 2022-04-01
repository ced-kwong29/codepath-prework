# Pre-work - *Memory Game*

**Memory Game** is a Light & Sound Memory game to apply for CodePath's SITE Program. 

Submitted by: Cedric Kwong

Time spent: 5 hours spent in total

Link to project: https://glitch.com/edit/#!/succulent-eastern-crate 

## Required Functionality

The following **required** functionality is complete:

* [x] Game interface has a heading (h1 tag), a line of body text (p tag), and four buttons that match the demo app
* [x] "Start" button toggles between "Start" and "Stop" when clicked. 
* [x] Game buttons each light up and play a sound when clicked. 
* [x] Computer plays back sequence of clues including sound and visual cue for each button
* [x] Play progresses to the next turn (the user gets the next step in the pattern) after a correct guess. 
* [x] User wins the game after guessing a complete pattern
* [x] User loses the game after an incorrect guess

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

## Video Walkthrough (GIF)

If you recorded multiple GIFs for all the implemented features, you can add them here:
![](https://user-images.githubusercontent.com/93562351/160945147-cb927c50-1aef-4b9c-ae96-1fcb087e8065.gif)
![](https://user-images.githubusercontent.com/93562351/160945104-04815440-073f-47aa-b573-e9f410a9992e.gif)
![](https://user-images.githubusercontent.com/93562351/160945165-cffd1a83-e2c6-4611-97b9-106fc4ef1145.gif)

## Reflection Questions
1. If you used any outside resources to help complete your submission (websites, books, people, etc) list them here. 
N/A

2. What was a challenge you encountered in creating this submission (be specific)? How did you overcome it? (recommended 200 - 400 words) 
I found that moving back and forth between the HTML, Javascript, and CSS file to be slightly challenging. Due to my only experience in programming in Python and C++, I was used to the idea of having to somehow import or reference files when coding in other files that were taking in information from them and were also in the same directory. With the memory game, I did not have to reference my html file in the css file or my javascript file, and the same applied to the other two files. Even while reading the instructions for the game, I found it difficult to wrap my head around the idea that a statement in an HTML fil like onclick=”guess(2)” would be calling on a function defined in my Javascript file because that line in the HTML file gave no indication of where 'guess()' came from. Before working on the game, I assumed that integrating HTML, CSS, and Javascript together required statements that referenced the other files before calling on methods or data from them similar to how in Python, one would need to import a module into another module to call on the imported file's methods or data. Getting used to this idea required me to simply add extra comments to my files in order to remind myself what file a specific piece of information or method that was being called came from while coding the 3 files together. Once I got used to the notion that I did not need to directly reference the other files, I was able to jump back and forth between the 3 files without needing to write down the reminders of the origins of a call to certain objects or methods and later removed all the extra comments.

3. What questions about web development do you have after completing your submission? (recommended 100 - 300 words) 
Something I have been wondering about is how frontend programming and backend programming come together as a whole. I had a friend introduce me to one of his projects for a hackathon. He said he had integrated Python with HTML and CSS. That had always fascinated me since my programming experience only included a year of Python and one quarter of C++. In the past, I had heard Javascript be referred to as a tool for both frontend and backend programming, and was surprised to find the language very similar to C++ as I was working on the Javascript file of the memory game.

4. If you had a few more hours to work on this project, what would you spend them doing (for example: refactoring certain functions, adding additional features, etc). Be specific. (recommended 100 - 300 words) 
With more time to work on the project, I would spend it on learning more about the functionality of Sound Synthesis Functions as well as more about the applications utilizing audio. In one of my classes this past year, a group of students had created a project intended to replicate a music synthesizer, where they created buttons that when clicked also played different pitches of audio as well as beats that resembled rhythm for users to create music. I do not know much about the making of music, but I find it fascinating how musical artists talk about the production of their music. At one point music could only be created through physical instruments. Nowadays, we have synthesizers that can create more various sounds than ever before.



## Interview Recording URL Link

[My 5-minute Interview Recording](https://drive.google.com/file/d/1VZKmkXRAVRxhoi3HtxGJaxCYCbFB3FK6/view?usp=sharing)


## License

    Copyright Cedric Kwong

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
