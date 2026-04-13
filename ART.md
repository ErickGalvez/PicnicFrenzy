## Asset Concept Art
  <p align="center"> Here are some textures, models and concepts implemented to tidy up the level and advance in the visual development of the game</p>
 <p> Smoothies are going to be NPCs that assist with specific tasks to main player, they can be upragded to do more tasks and have better capabilities </p>
 
<div align="center">
  <img src="https://github.com/user-attachments/assets/7b9585f2-5b5b-472f-ac00-9a1889e47c3b" alt="Smoothie_Character_Concept_V1" width="30%" height="auto"/>
  <img src="https://github.com/user-attachments/assets/e71fa2f0-3255-4fdd-8fda-1fee976f9bee" alt="Smoothie_Character_Concept_v1" width="30%" height="auto" />
  <img src="https://github.com/user-attachments/assets/9317f0c5-e78f-4831-8ed7-926b79aa8d11" alt="Smoothie_Character_Concept_v1" width="30%" height="auto"/>
  </p>
</div>


## Proof of concept #1 - Technical aspects of water simulation integration to ue5
  <li><b>What is the most native UE5 option available?</b></li>
    <p>Alembic cache simulation is the most standarized way of managing particle simulation mesh sequences between different particle simulation softwares/plug-ins, this format can be imported into Unreal Enigne 5, it has a smooth integration and intuitive use inside Unreals animation framework</p>
  
  <ul>What is the best looking integration of the simulation?</ul>
  
  <ul>What is the most native UE5 option available?</ul>
  
  <ul>What is the most efficient/best performance way of using fluid simulations on UE5</ul>
    <ul>Baking resulting fluid simulation to use top part of the cache as a height map</ul>
        <p>Turning manifold geometry given by a fluid simulation into a height map is the most efficient way that comes to mind, 
          The blending_sim_1.abc does note involve drastic geometry movement in its lower part, due to liquid filling completely and vortex force pushing the liquid to the walls of the blender</p>
          <video src="https://github.com/user-attachments/assets/8e68241d-9d17-4a1f-a2fe-1cff3f13f492" alt="Smoothie_Animation_Compare_V1" width="20" height="auto" align="left"/>
          
   
  <ul>How it affects performance on mobile devices?</ul>       
  To Do: Perf testing for devices: Its necessary to deploy a mobile build 0.1 with the finished asset and its variations to analyze their performance and get a clear insight as to how the asset can be optimized with different implementations
  <img width="1372" height="900" alt="WaterSim_Scheme" src="https://github.com/user-attachments/assets/dd14ebba-d2af-4e98-a4ec-1bb2dd854628" />
  
  <li>Smoothie Material</li>

  <li>Pouring liquid animation</li>
  <li>Some Extra background assets</li>
  <li>FruitBag</li>
  <br>
  <br>
