# GM-Spaceship-Game
2D spaceship game in GM

One of first games I mstarted in GM

6-28-2017

implemented aray based minimap system. Can't have minimap_instance_add function called in planets because global.minimap array not initialized. Have to add these manually in ship create event. Dynamically created objects created in course of game like enemy ships work though.