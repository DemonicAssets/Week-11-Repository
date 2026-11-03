# CS110 Action 11A — My seminar and engine experiment

Learner / folder: [add your name or approved identifier]
Engine route: unity
Work mode: team
My personal repository / one Canvas submission link: https://github.com/DemonicAssets/Week-11-Repository/tree/main/Action%2011A/Chris
Team repository: https://github.com/DemonicAssets/Week-11-Repository/tree/main/Action%2011A

## GitHub checks before and after work

[Not recorded yet — complete this section.]

## 1. Our Attention Accord — shared plan/reference

Huddle start / end (at least 10 minutes):
Start: 12:45
End: 12:55

Team / lead / production purpose:
Our team is learning how to use C# programming in Unity to create and control game objects. Our goal is to understand classes, variables, methods, and components.

Member → focus question → capture method → promised contribution:
Me → How do C# classes and methods work in Unity? → Lecture notes and Unity screenshots → Explain how to move, rotate, and change the color of a game object.

Other team members → [Add their focus questions, capture methods, and contributions.]

Plan file, board photo or shared-document link:
[Insert actual GitHub file, shared document, or whiteboard photo link.]

Return-to-team time and how we will use the findings:
[Actual meeting time]. We will share our findings, compare our Unity experiments, discuss problems, and use what we learned to improve our game development project.

## My personal attention brief

I will investigate:
How C# classes, variables, and methods are used in Unity to control game objects.

I need to understand:
How Start() and Update() work, how components are attached to objects, and how to move, rotate, and change the color of objects.

I will capture:
Lecture notes, C# code examples, screenshots of my Unity project, and results from my experiments.

I will return with:
An explanation of how Unity uses C# to control game objects, examples of movement, rotation, and color changes, and what I learned from testing.

My evidence will be saved at:
My personal GitHub repository in my Week 11 assignment folder.

How this helps our team build:
It helps our team understand how to use C# scripts in Unity, create reusable objects, organize our code, and develop games more efficiently.

## 2. My seminar notes

[Not recorded yet — complete this section.]

## My host translation

Engine / version / language:
Unity / [Enter installed Unity version] / C#

Familiar C# idea → engine equivalent:
C# classes become scripts attached to GameObjects in Unity. Variables store information, methods perform actions, and components control object behavior. Unity uses transform.Translate() for movement and transform.Rotate() for rotation.

Who calls initialization and repeated updates?
Unity automatically calls Start() once before the first Update() when the script is enabled. Unity calls Update() every frame while the script is active and enabled.

One discovery I shared with the team:
I learned that Unity uses the same C# concepts we practiced in Visual Studio. Unity already provides a game loop and built-in methods, making it easier to create objects that move, rotate, and change color without programming everything from scratch.

## 3. My individual base

My source files / scene:
TranslateObject.cs, RotateObject.cs, and ChangeObjectColor.cs. My Unity scene contains a cube named MyMarker with all three scripts attached.

Starting values and prediction:
I will start with a movement speed of 1 and rotation speed of 90 degrees per second. I predict the cube will move, rotate continuously, and change to the color selected in the Inspector.

Actual movement / rotation / color result:
[Complete after testing.] I will record whether the cube moved at the expected speed, rotated continuously, and displayed the selected color.

The class/property/method responsible:
TranslateObject uses transform.Translate() to move the cube. RotateObject uses transform.Rotate() to rotate it. ChangeObjectColor changes the material color. Update() handles repeated movement and rotation, while Start() handles initialization.

Frustration or error, and how I investigated:
[Describe an actual issue, or write "No errors occurred" if everything worked.] I will check the Unity Console, Inspector settings, and script attachments to investigate any problems.

## 4. My experiment and return to the team

My question / prediction:
What happens when I change the movement speed of a cube in Unity? I predict that increasing the speed will make the cube move faster without changing its rotation or color.

Change beyond the base:
I will change the cube's movement speed from 1 to 2 in the Inspector and compare the results. I will also create two instances of the same prefab with different speeds.

Observed result or exact error / next step:
[Enter actual result after testing.] I expect the cube with speed 2 to move twice as fast as the cube with speed 1. If there are errors, I will check the Console and script settings.

Prefab or saved scene and two-instance comparison:
I will create a prefab of MyMarker and place two instances in the scene. One will have speed 1, and the other will have speed 2. Both will use the same scripts but have different movement speeds.

What I promised → what I actually returned:
I promised to investigate how C# scripts control Unity objects. I will return with my code, screenshots, experiment results, and an explanation of movement, rotation, and color changes.

My interpretation/recommendation and supporting evidence:
Changing variables in the Inspector allows developers to adjust object behavior without rewriting the code. I recommend using reusable scripts and prefabs to make game development more organized. My evidence will include screenshots of the Inspector and the two objects.

How the team will use it; what I learned from someone else:
Our team can use these scripts to create moving objects and reusable game elements. From the lecture, I learned that classes are blueprints, variables store information, and methods perform actions. [Add one specific thing learned from a teammate.]

Checked source or supplied-claim correction:
I checked Unity's documentation to understand how Update(), Transform, and prefabs work. One important clarification is that prefabs are reusable templates, but each instantiated object still exists separately and uses resources. Prefabs help organize and reuse objects, but they do not automatically eliminate memory usage.

## Source and evidence

[Link my project, scene, whiteboard screenshots/photos, base/extension evidence and checked source. All my authored work belongs in this personal repository.]

My individual engine base status: [working / blocked — explain].
My individual extension status: [result / error and next step].
Help received: [describe].

Commit and push all my authored work, including board captures, notes, project and evidence, to my personal repository. Open the pushed files/images and test the personal URL and applicable team URL/member links. Submit the one personal repository URL in Canvas; this README contains the team link if applicable. This export is not Canvas submission.
