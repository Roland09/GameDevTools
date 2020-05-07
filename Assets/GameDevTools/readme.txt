==================================
Game Dev Tools
==================================

About
----------------------------------
Package contains various tools for prototyping, common and for dedicated assets.

In order to make use of dedicated assets you need to activate various scripting define symbols.

PostProcessing
----------------------------------
* various postprocessing profiles which were used in the respective game prototypes

Enviro
----------------------------------
Runtime weather and time changes
* activate script via scripting define symbol: ENVIRO
* create gameobject and add EnviroKeyHandler to it
* optionally add EnviroWeatherAndTime prefab and assign weather and time text gameobjects to the the weather and time textmesh slots
* change weather and time via keyboard shortcuts during runtime


Screenshot
----------------------------------
Add the script to a gameobject. During runtime hit the key which was specified in the inspector in order to create a screenshot