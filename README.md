# Godot-Bullet-Hell-Optimization-Test
Seeing how many conventional bullets I can run in Godot at once with working collisions. Feel free to download and optimize further.

Inspired by GDQuest's video, I tried to replicate results. 
This uses pooling to spawn bullets and the PhysicsServer to process collisions. 
A multimeshinstance renders the sprites. 
I was only able to get a max of 3500 bullets on screen at 60 fps.
