# Puzzler Project for VR Nanodegree

## Introduction

This is my submission for the Udacity VR Developer Nanodegree Puzzler project. I designed and built a mobile VR application that takes a user through a dungeon-based memory puzzle. I took an iterative approach to creating the app, sketching some initial designs before user testing the app throughout the creation stages. I incorporated the feedback from user testing into each iteration of the Puzzler app.

### Initial Foundations

The Udacity team provided the base materials and foundational scripts, which I used to build out the app. The starting point was to achieve a realistic world scale from the initial assets and iterate from there. 

## Puzzler

I iterated on the app based on feedback from the family members and colleagues I asked to user test the project. The overall approach was based on the advice given by the Udacity team in the course. The user testing definitely helped to produce a much better outcome than the initial versions, and helped produce an easy entry for inexperienced VR consumers.

#### Playthrough
[![Puzzler Demo](http://i.imgur.com/676Rr1C.png)](http://www.youtube.com/watch?v=tbdKSqYSYDE "Puzzler project from VR Nanodegree")


#### Visual Cue
![Puzzler Demo](http://i.imgur.com/04yCUM5l.png)

## Process

### Statement of purpose

_Puzzler is a mobile VR application for new VR users which challenges them to solve a familiar type of puzzle in a new way._

## Persona

#### Elsie
![Elsie](http://i.imgur.com/KXxgzt6m.png)

Elsie is a 39 year old mother who likes to fire up her smartphone when the kids are in bed. She needs something interesting to entertain her when she finally gets to relax on the sofa after a long day of parenting.

Her VR experience is limited to a couple of cardboard apps. She only has about 30 minutes to kill between putting the kids to bed and her husband getting home from work. She likes puzzle-based games and after trying some cardboard apps round a friend's house she has her own viewer, but hasn't used it yet.

She's got no experience of a proper VR HMD, although she thinks she might try one if she enjoys VR on her phone.

## Sketches

I started out by sketching some of the key elements of the experience, trying to prototype out the options in the least expensive way, before building the app in Unity.

### Initial Concept Sketches

![Sketch1](http://i.imgur.com/2OkCrn2m.jpg) ![Sketch2](http://i.imgur.com/cgbQ3DWm.jpg)
![Sketch3](http://i.imgur.com/UaPFZblm.jpg) ![Sketch4](http://i.imgur.com/71nDCwrm.jpg)

#### Start and Re-start UIs

![Start UI 1](http://i.imgur.com/t4qa6tUm.png) ![Start UI 2](http://i.imgur.com/Sckxexhm.png)
![Re-start UI 1](http://i.imgur.com/epGSkt9m.png) ![Re-start UI 2](http://i.imgur.com/eab7rvQm.png)

## User Testing

### User Test 1 - Scene and Atmosphere

The first user test I conducted was designed to check the scale of the scene felt life-size, and that the atmosphere felt a bit creepy. I tried modelling the door on a real world door size before finalising the build for the user test. I was feeling pretty confident and looked forward to trying it out with a real-world user. I got some really interesting feedback from the test: The size was good and felt realistic, the mood felt "not nice, and a little eerie" without being "overly creepy". The unexpected feedback was the floor felt "too high, like it" was "around my waist." After some camera placement tweaks, the user confirmed the scene felt better.

### User Test 2 - GUIs

The next round of testing was designed to test the start GUI in the app. This test was relatively straightforward. The feedback was positive: The size and scale of the UI panel "felt about right", the text was "perfectly legible", and the user understood what the panel UI was for, and what would happen if they selected the start button.

![Start UI](http://i.imgur.com/YEIHb4Bm.png)

### User Test 3 - Movement

I tested this with a couple of different users, and got some different responses. The first time I tested the movement mechanic was with an experienced VR user. They felt that the movement was "slow and steady", and generated no simulator sickness. The user felt there was "no weirdness in the movement", although they described a "weird speeding up then slowing down" towards the end. The second set of user testing was with an inexperienced VR user. This yielded interestingly different results. This user found the movement mechanic from the game scene through to the final UI to be "too fast in the initial movement", leaving them to feel "a bit disoriented". They also felt they were about to "hit their head on the wall on the way out of the dungeon." I decided to focus more on the feedback from the inexperienced user, as this is more my target audience for the app. I made the final movement twice as slow as I initially set, and found the user was much happier with the speed set to 4 seconds.

### User Test 4 - Final Mechanic

I conducted some final user testing with the inexperienced VR user, and some other people who hadn't yet tested the app. Everyone reported a pleasant experience, and resulted in no further changes to the app.

## Breakdown of the Final Result

### Start

The user starts the experience interacting with a simple Start UI panel, where they start the game by selecting the "Start" button.

### Game in the Dungeon

The user is taken into the main area of the game, in the dungeon. The user has to complete a simple pattern recognition game, with visual and audio clues to help guide them as to their choices. If they make the wrong choice, they get feedback and the sequence starts again. If they make the right selections, they are taken out of the dungeon.

![Inside the Dungeon](http://i.imgur.com/cqnN0N3m.png)

### Success and Restart

Once the user has been successful they are presented with a final UI panel which congratulates them on their success, and offers them the chance to re-start the game. The user is taken back to the start point if they select the "Restart" button.

![Re-start UI](http://i.imgur.com/Bfc1pnsm.png)

## Conclusion

### Thoughts on the Process

This was an eye-opening experience. The iterative design process, the various elements that go into a successful design (ergonomics, UI, movement, feedback), and the user testing process were enjoyable and really informative. I definitely feel more confident in designing and creating VR experiences going forward with this new toolset.

### Link to Additional Work

If you're interested in seeing the other VR projects I've created, please see the rest of my [Github profile](https://github.com/jonathanmundy).
