# CS110 Action 11A — My seminar and engine experiment

Learner / folder: [add your name or approved identifier]
Engine route: unity
Work mode: team
My personal repository / one Canvas submission link: https://github.com/DemonicAssets/Week-11-Repository/tree/main/Action%2011A/George
Team repository: https://github.com/DemonicAssets/Week-11-Repository

## GitHub checks before and after work

Everything works in the github.

## 1. Our Attention Accord — shared plan/reference

CS110 Game Development Team. Lead: [Leah Aluni]. Our purpose is to research Unity, understand its tools and features, and learn how to use it to develop our game's story, characters, and environment.

## My personal attention brief

I will investigate:

How Unity works and how C# programming connects to game development. I will research GameObjects, classes, components, movement, rotation, color changes, and how Unity can help us create our game's world and story.

I need to understand:

How classes create objects, how variables store information, how functions perform actions, and how C# scripts control objects in Unity. I also need to understand how Unity's Prefabs allow us to reuse objects.

I will capture:

Written research notes, screenshots of my Unity project, examples of C# scripts, and a sketch explaining how classes, objects, data, and methods work together. I will also record my experiments and results.

I will return with:

A better understanding of Unity, notes about its features, a working object that can move, rotate, and change color, and one additional experiment. I will also bring ideas for how Unity can help develop our team's game.

My evidence will be saved at:

My personal CS110 GitHub repository, inside my Github (George Folder) under 11A/. My evidence will include my README notes, Unity project files, screenshots, whiteboard sketches, and experiment results.

How this helps our team build:

My research will help the team understand how Unity works and how we can use its tools, C# scripts, reusable objects, and environments to develop our game world and bring our story to life.

## 2. My seminar notes

Class and object in my own words:

A class is a blueprint that describes how something is created and what it can do. An object is something created from that blueprint. For example, a Character class can be used to create different characters in a game.

One field/property and one method:

Field/property: Health – stores how much health a game character has.

Method: Move() – tells the character to move.

My question coming into the seminar:

How do classes, objects, fields, properties, and methods work together in Unity, and how can I use them to create characters and objects for our game?

## My host translation

Engine / version / language:

Engine: Unity Editor
Version: Unity 6 (confirm the exact version installed in Unity Hub).
Language: C#.

Familiar C# idea → engine equivalent:

In C#, we use classes, variables, and methods to create programs. In Unity, we use C# classes that inherit from MonoBehaviour and attach them as scripts to GameObjects. Variables store information, and methods control what objects do.

Who calls initialization and repeated updates?

Unity automatically calls the script's initialization methods, such as Awake() and Start(). It also calls Update() repeatedly every frame while the script is enabled. The Unity engine manages when these methods run.

One discovery I shared with the team:

I learned that Unity uses C# and object-oriented programming, just like what we studied previously. Unity's Start() method runs once when a script begins, while Update() runs every frame. This allows us to control objects and create interactions in our game.

## 3. My individual base

My source files / scene:

Unity Editor – SampleScene. My test object is a 3D Cube. My C# script is attached to the Cube to control its movement, rotation, and color.

Starting values and prediction:

Starting position: X = 0, Y = 0, Z = 0. Starting rotation: X = 0, Y = 0, Z = 0. Starting color: White.

I predict that changing the Transform values will move and rotate the cube, and changing its material color will change its appearance.

Actual movement / rotation / color result:

The cube should move to a new position, rotate around an axis, and change from its original color to the selected color when the script runs. I will record the actual results after testing it in Unity.

The class/property/method responsible:

The Transform class controls the cube's position and rotation. The position property controls where the cube is located, the Rotate() method changes its rotation, and the Renderer and material.color properties control its appearance.

Frustration or error, and how I investigated:

I needed to understand how to connect a C# script to a GameObject. I investigated the Inspector, checked that the script was attached to the Cube, reviewed the code, and checked the Console for errors.

## 4. My experiment and return to the team

My question / prediction:

Can I create two copies of the same object in Unity and give each one different properties? I predict that I can use a Prefab to create reusable objects and customize each instance.

Change beyond the base:

I will experiment with changing the cube's size, position, and color. I will also create a Prefab so I can reuse the same object multiple times.

Observed result or exact error / next step:

I will test the changes in Unity and record whether the objects behave as expected. If something does not work, I will check the Inspector, C# script, and Console to identify the problem.

Prefab or saved scene and two-instance comparison:

I will save my Cube as a Prefab and create two instances in the scene. I will compare their positions, sizes, and colors to understand how reusable objects work in Unity.

What I promised → what I actually returned:

I promised to research Unity, learn how its tools work, and complete an individual experiment. I will return with research notes, screenshots, a saved Unity scene, a Prefab experiment, and information that can help our team develop our game.

## Source and evidence

[Link my project, scene, whiteboard screenshots/photos, base/extension evidence and checked source. All my authored work belongs in this personal repository.]

My individual engine base status: [working / blocked — explain].
My individual extension status: [result / error and next step].
Help received: [describe].

Commit and push all my authored work, including board captures, notes, project and evidence, to my personal repository. Open the pushed files/images and test the personal URL and applicable team URL/member links. Submit the one personal repository URL in Canvas; this README contains the team link if applicable. This export is not Canvas submission.
