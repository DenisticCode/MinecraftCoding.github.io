# The Basics

> Pathway and CustomModelData

These are the basic material you need for your custom item resource pack. 
The two json files are important for the model and pathway to the textures of your specific generated model. 
In the 4.json file has this ->

"0": "item/custom_textures/cyberaxetexture",
		"particle": "item/custom_textures/cyberaxetexture"

  This is the pathway for the texture for the custom model and your custom item.

  In the diamond_axe.json file it had this ->

  "overrides": [
        {"predicate": {"custom_model_data":4}, "model": "item/diamond_axe/4"}
    ]
}

this is the pathway to the 4.json file so that it loads your custom item.

> Generate and Load to Minecraft

You can generate your custom item through this command in chat or through using command block: /give <player> minecraft:diamond_axe{CustomModelData:4} or you could use the https://mcstacker.net/ to customise item, but be sure to give it a CustomModelData!

> End

Thank you for reading I hope this helps you on your way to custom items in minecraft. Enjoy!
