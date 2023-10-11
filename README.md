# KarioMartAssignmentGP23

I decided on Kario Mart as my assignment. I made three scenes for each separate racing track. Using the open sprite shape object and the “edit spine” function I created the outline of the tracks. I used the same method to make the walls around the tracks. I added an edge collider to the walls and a box collider to the car. (player). 

I made the controls of the car using the GetAxis functions to determine the rotation and speed of the car. I then called the rigidbody component of the car object and applied relative force to accelerate and steer the object. 

The speed power-ups check for collisions and destroy themselves upon colliding with the player. The script simply adds onto the variable responsible for acceleration speed in the CarController script. 

I was not able to finish the main menu and pause function in time. My intention was to create the menu using simple buttons, an event system, the scene manager and OnClick functions for each individual button to load the given scene.
