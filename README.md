<img src="fig/randomwangran-post.png" align="right">

#### If the commit is a rock, what it looks like when air blows it?
I've say snappyHexMesh is smart! It kinda know what I was asking for.
This is just the 1st shot and I should be grateful no error throw out
right way.

As you can see, I need the air around my "commit rock" to be meshed
but not the "commit rock" itself.

![img](fig/2021-03-02_14-54-01.png)

Second, only the basement of my commitment are meshed.

![img](fig/2021-03-02_14-56-05.png)

Third, too much computation.

    Layer mesh : cells:864806  faces:2848196  points:1120129

Mesh sucessful.
![img](fig/2021-03-03_12-09-49.png)
##### mesh generation
##### case setup
To project to a plane at y=0.

Use the Calculator filter to project each point (x, y, z) to (x, 0, z).

Turn on Coordinate Results and set the expression to `coordsX*iHat + coordsZ*kHat`

Use \`IntegrateVariables\` filter to give you a magic number.

For my profile, the number is: 7591.94.



#### If the commit is a bulk of water, what it looks like when a sonar scans it?
#### If the commit is a bridge, what it looks like when a force applies to it?
#### If the commit is a mountain, what it sounds like when you make noise from 7 meters away?
#### If the wind attacks from the top/right/left, what is a drag coefficient ?
#### If you throw this thing into the sky, what is the trajectory looks like?
#### If a bullet attacks it, what it looks like?
