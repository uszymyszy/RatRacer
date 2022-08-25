# Rat Racer Press Kit

>title: Rat Racer
><br>
>developer: Jacku
><br>
>publisher: uszymyszy [ushi mishi]
><br>
>description: a tiny game with physics simulations hidden under two motorized rats :)
><br>
>game modes: player vs. player, player vs. AI, online multiplayer
><br>
>links: [Steam](https://store.steampowered.com/app/1199360/Rat_Racer) | [Twitter](https://twitter.com/uszymyszy) | 
[Reddit](https://www.reddit.com/r/Unity3D/comments/eax1kr/i_applied_your_comments_to_car_physics_and_here/) | 
[Discord](https://discord.gg/bWzGe5wQpY) | 
[YouTube](https://www.youtube.com/watch?v=ts1PP9cTiks)  

<br>

### Intro
Rat Racer is a physics-based car simulator. This is not a typical arcade game - everything is calculated in real time by Nvidia PhysX engine so the drive model is more difficult to learn at the beginning, but it gives you much more satisfaction when you master it over time.
![](screenshots/racetrack_old_station_01.jpg)
<br>

### Sandbox
All tracks are virtual sandboxes, you can drive everywhere and do anything what your car physics allows. All collisions, jumps, spins are unique due to real time physics and such environment.
![](screenshots/sandbox_01.jpg)
 Each track has different ground types - dirt, tarmac, sand which can also reacting with the car.
![](screenshots/graphics_details_01.jpg)


<br>

### Physics and car handling
The car is reacting to different ground types like dust, dirt, microbumps and road inclination. Use the analog braking and handbrake to keep it stable. Driving at high speeds may be unpredictable, try to feel the car reactions and then gradually speed up or use controlled drift.
![](screenshots/racetrack_village_02.jpg)

<br>

Watch out for your rat - if you drive too aggressively it may fall out of the car due to stronger forces. Also, if you push the engine to the max, it can sometimes catch fire.
![](screenshots/fall.jpg)
By using analog controls you can make jumps and landings safer. When spinning, try to align your front wheels with flying direction, brake slightly when the wheels contact the ground - it may help to loose velocity and prevent your rat from falling out of the car.
![](screenshots/forces_04.jpg)


<br>

### Graphics & Optimization
The game is quite good optimized - it is possible to get about 300 FPS on GeForces and AMD's. For old laptops there is special Low Detail mode to keep 40 FPS.
![](screenshots/sandbox_04.jpg)
![](screenshots/racetrack_village_01.jpg)


<br>

### Multiplayer
You can play with a friend on the same keyboard, there is also experimental online multiplayer. Two analog gamepads are also supported (Xbox).
![](screenshots/racetrack_wooden_01.jpg)

<br>

### Rat AI
The RatAI module is quite advanced, the opponent can be passive or aggressive depending on your driving. It can decide to push or avoid obstacles, you can also form a barricade from different elements and AI will try to solve it.
![](screenshots/oil.jpg)
![](screenshots/chase.jpg)

<br>






### Photo Tool
During the Pause Menu the mouse works like camera focus - use it to compose your shot and press F12 to take a picture.
![](screenshots/forces_02.jpg)

<br>

### How the tracks are created
The race track creation process is definitely the hardest part of this game. The track should feel like a real place and the roads should be natural, with good balance of speed and handling. 
![](screenshots/sandbox_05.jpg)
<br>
 Jacku, the main dev says: for this purpose I wrote a 2D generator which can create many track iterations. After testing many of them it is easier to pick the best parts from each and see how different elements works together.
<br>

![](screenshots/track_generator_2D.gif)


<br>
Last year I moved the generator to 3D to have the overview of the track from game perspective and it greatly speed up the creation process. Now I'm experimenting also with AI generators like DALL-E and Midjourney so the next tracks should be more realistic and playable.

![](screenshots/track_generator_01.jpg)
![](screenshots/track_generator_02.jpg)


### Track Randomization
There are many random things which make each racing different - AI can sometimes miss the checkpoints so you never know who will win. Car engines can have a failures. The boxes on the road are filled with random stuff - you never knows if it's safe to collide with. The drone-like camera sometimes look at weird angles so you cannot clearly see your position. Some of the track locations are covered by obstructions so you need to use your intuition when your car is not visible for few seconds. There are no bounds on track so beware of the edges - or force your opponent to drive there.
![](screenshots/forces.jpg)

<br>


<br><br><br>



### Other screenshots:
![](screenshots/racetrack_old_station_02.jpg)
![](screenshots/racetrack_old_station_04.jpg)
![](screenshots/racetrack_old_station_03_top_view.jpg)
![](screenshots/photo_tool_01.jpg)
![](screenshots/photo_tool_02.jpg)

![](screenshots/racetrack_village_03.jpg)
![](screenshots/racetrack_village_04.jpg)

![](screenshots/racetrack_wooden_02.jpg)
![](screenshots/racetrack_wooden_03_top_view.jpg)

![](screenshots/sandbox_02_the_village.jpg)
![](screenshots/sandbox_03.jpg)
![](screenshots/forces_03.jpg)
![](screenshots/handbrake.gif)
