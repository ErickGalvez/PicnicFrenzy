
# PicnicFrenzy




## Demo 1 Picnic Frenzy Smoothie Cycle overview:
4 tasks will compose the Smoothie Cycle v1
<li>Pick item</li>
<li>Blend</li>
<li>Serve</li>
<li>Deliver</li>

<p align="center">
  <img src="https://github.com/user-attachments/assets/c931b1ce-33fe-4e9e-8c12-72c2e9bbd3c8" alt="Sublime's custom image" width="350" height="auto"/>
</p>

i'll develop this cycle of actions breaking down the steps into separate mechanics.
I decided to start this project from a project template in UE5 called TopDown game, since this is the closest template to the genre of game im aiming for (Tycoon Style game)
early development will be Blueprint based, since this aproach lays an easy framework to start prototyping, if i think is convenient for the game to be based on C++, i will later parse this prototype to a C++ code.

As a solo developer for this project, ill also be in charge of the concept art, modelling, developing and testing, this Log will also feature concept art for characters, assets and levels

<p align="center">
  <img src="https://github.com/user-attachments/assets/7b9585f2-5b5b-472f-ac00-9a1889e47c3b" alt="Smoothie_Character_Concept_v1" width="350" height="auto"/>
</p>

Here's a first idea of blocking an area to test the interaction with each workstation

<p align="center">
  <img src="https://github.com/user-attachments/assets/60209b8a-a8bb-40f1-9b29-3ec9b04a2fd7" alt="Smoothie_Character_Concept_v1" width="350" height="auto"/>
</p>

Making sure that the logic of the character knows that he is entering the area of a workstation, and gets the reference to the component from the area entered is important, so it can be used later on to know which object should be interacting with the player, doing it this way allows us to place multiple instances of a workstation and not only getting the parent component, but specifically that instance of the workstation, thus keeping this instances in diferent states, or with different local information.

This brings me to the first implemented piece of logic in the game, we are going to print whenever the player enters an area, the name of the corresponding worksation

<p align="center">
  <img src="https://github.com/user-attachments/assets/aa6d54bb-891a-44ac-b99d-9909595fdf6c" alt="Smoothie_Character_Concept_v1" width="400" height="auto"/>
  <img src="https://github.com/user-attachments/assets/16457c3a-c1d0-4778-92a6-aa5df722597c" alt="Smoothie_Character_Concept_v1" width="1080" height="auto"/>

</p>

here are some textures, models and concepts implemented to tidy up the level and advance in the visual development of the game

<p align="center">
  <img src="https://github.com/user-attachments/assets/e71fa2f0-3255-4fdd-8fda-1fee976f9bee" alt="Smoothie_Character_Concept_v1" width="500" height="auto"/>
  <img src="https://github.com/user-attachments/assets/9317f0c5-e78f-4831-8ed7-926b79aa8d11" alt="Smoothie_Character_Concept_v1" width="500" height="auto"/>
</p>

https://github.com/user-attachments/assets/b57a8887-2e1e-4ef7-ac4b-278a2b920921


## Demo 2 Smoothie Cycle - Step 1: Pick Item:
We get near an object we want to pick, press E, the instance of the object picked will be destroyed from the map, and we are adding 1 to the "Fruit" variable, used for tracking how many fruits the player carries at any given moment

<p align="center">
<img src="https://github.com/user-attachments/assets/cf20a560-145a-41bd-bf1a-a074596a788e" alt="Smoothie_Character_Concept_v1" width="600" height="auto"/>
</p>


https://github.com/user-attachments/assets/69c5b0d2-2193-4721-bf62-a40f25c253cd


## Demo 3 Smoothie Cycle - Step 2: Blending: 
### Funcitonality:
<li>Drop Ingredients into blender</li>
<img src="https://github.com/user-attachments/assets/25441574-324f-420d-a328-89ebb371903d" alt="Smoothie_Character_Concept_v1" width="600" height="auto"/>
![blender]()

To enter a fruit or item in a blender it must first evaluate if the player has any fruits added to their invenotry, if there are, it will proceed to substract one fruit from the inventory 
(Which will be represented by the variable before implementing any Inventory functionality to the game), 
For the first iteration of the Blending functionality, the state of the blender will be now at full capacity by adding one fruit.

https://github.com/user-attachments/assets/655c9b2e-a9c1-464b-b71e-7ed251e746dd

This First iteration only detects when Fruit has been entered to the Device It shows a placeholder with either: Purple for empty, Orange for Fruit entered
## State Machine V1:
2 states:
<li>Full</li>
<li>Empty</li>

<p align="center">
<img src="https://github.com/user-attachments/assets/bbc4d3db-cfe1-4949-8198-5353586a20b4" alt="Smoothie_Character_Concept_v1" width="600" height="auto"/>
<img src="https://github.com/user-attachments/assets/dc0d3e75-7707-4e16-aed1-056f73e53ba3" alt="Pick Fruit Mechanics" width="600" height="auto"/>
</p>




On later iterations a gradual capacity for the blender will be implemented as illustrated:


<li>Blender State Machine</li>

### Art:
<li>Blending liquid simulations</li>
<li>Smoothie Material</li>
<li>Pouring liquid animation</li>
<li>Some Extra background assets</li>
<li>FruitBag






Developed with Unreal Engine 5

