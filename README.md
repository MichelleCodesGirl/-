🤖 Side-Scrolling Grapple-Bot
A fast-paced, physics-based platformer where mobility is everything. Swing, climb, and maneuver through levels using a high-tech grappling hook to reach the finish line. And don´t worry if you fail you don´t restart the whole game only the round!

 Play the Game
https://michellecodesgirl.github.io/Grapple-Bot/

How to Play
Move: Use the A and D keys (or Arrow Keys) to run.
Grapple: Use your Mouse to aim and Left Click to fire your grapple at surfaces.
Release: Let go of the click

Objective: Navigate through the obstacles as quickly as possible without falling off the map!

Built With

Engine: GitHub
Language:HTML

Features
Physics-Based Movement: Realistic swinging mechanics that rely on momentum.
Smooth Side-Scrolling: A camera system designed to keep the action centered.
Dynamic Levels: Challenging terrain designed specifically for grappling maneuvers.
The Grapple Physics: Getting the rope to feel "snappy" but also follow realistic momentum was the biggest challenge. I had to calculate the distance between the player and the anchor point constantly to ensure the swing felt natural rather than floaty.
The Follow Camera: In a side-scroller, if the camera moves too fast, it’s disorienting; if it’s too slow, the player falls off the screen. I implemented a lerp (linear interpolation) function to make the camera "lag" slightly behind the bot, creating a much smoother visual experience.
Collision Detection: Making sure the grapple only sticks to specific surfaces required careful tagging of game objects. I spent a lot of time debugging why the bot would sometimes try to "swing" off of thin air!
