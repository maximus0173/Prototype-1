# Prototype-1
Project prepared for Unity Junior Programmer Course: Create with Code 1: Bonus Features 1<br/>
To run this project in Unity, you must have "Assets/Course Library" folder from tutorial.<br/>
<br/>
From tutorial project I've created real endless runner with the cars driving both directions and plane dropping crates. It's not polished, just basic functionality.<br/>
My submission: <a href="https://learn.unity.com/submission/618d53eeedbc2a0020de4bef">https://learn.unity.com/submission/618d53eeedbc2a0020de4bef</a><br/>
Endless runner is in scene: Assets/Bonus Features 1/Scenes/Bonus Features 1<br/>
<br/>
The effect of "endless" works that, EndlessManager constantly checks that the player's car has not exceeded the ResetPosition. If it does, it sends a signal to the player's car and all other cars and plane to move closer to the start of the road.<br/>
The camera follows the player's car, so it is also moved and the player does not notice the difference.<br/>
Additionally, the environment also tracks the player's car position and moves with it.<br/>
