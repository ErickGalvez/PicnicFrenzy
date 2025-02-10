
# PicnicFrenzy

## Day 2: 15/01/2025 Demo 1 Picnic Frenzy:
4 tasks will compose the Smoothie Cycle v1, we are going to focus on a sub-mechanic, the idea is to be able to pick up stuff, basically, we get near an object we want to pick, press E, the instance of the object picked will be destroyed from the map, and we are adding 1 to the "Fruit" variable, used for tracking how many fruits the player carries at any given moment

<p align="center">
<img src="https://github.com/user-attachments/assets/cf20a560-145a-41bd-bf1a-a074596a788e" alt="Smoothie_Character_Concept_v1" width="600" height="auto"/>
</p>


https://github.com/user-attachments/assets/69c5b0d2-2193-4721-bf62-a40f25c253cd


## Day 1: 14/01/2025 Demo 1 Picnic Frenzy:
4 tasks will compose the Smoothie Cycle v1
-Pick from Fridge
-Blend
-Serve
-Deliver
Developed with Unreal Engine 5
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








