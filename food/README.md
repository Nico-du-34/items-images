## General
Add These To Your qb-core/Shared/Items.Lua

## Credit to Contributors
 - [IDRP](https://github.com/idrp/qb-uwu)
 - MrFuRoX @ [Project Boosted](https://github.com/Project-Boosted)


----------  General  ----------  General  ----------  General  ----------  General  ----------
```lua
-- BURGERSHOT
	["shotnuggets"] 				 = {["name"] = "shotnuggets", 			  		["label"] = "Shot Nuggets", 			["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-shotnuggets.png", 	["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,	   	["combinable"] = nil,   ["description"] = "Burgershot Nuggets" },
	["shotrings"] 				 	 = {["name"] = "shotrings", 			  		["label"] = "Ring Shots", 				["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-shotrings.png", 	["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,	   	["combinable"] = nil,   ["description"] = "Burgershot Onion Rings" },
	["heartstopper"] 			 	 = {["name"] = "heartstopper",       			["label"] = "HeartStopper",	 			["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-heartstopper.png", 	["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Heartstopper" },
	["shotfries"] 		 			 = {["name"] = "shotfries",       				["label"] = "Shot Fries",	 			["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-fries.png", 		["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Shot Fries" },
	["moneyshot"] 		 			 = {["name"] = "moneyshot",       				["label"] = "Money Shot",	 			["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-moneyshot.png", 	["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Money Shot" },
	["meatfree"] 		 			 = {["name"] = "meatfree",       				["label"] = "Meat Free",	 			["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-meatfree.png", 		["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Meat Free" },
	["bleeder"] 		 			 = {["name"] = "bleeder",       				["label"] = "The Bleeder",	 			["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-bleeder.png", 		["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "The Bleeder" },
	["torpedo"] 		 			 = {["name"] = "torpedo",       				["label"] = "Torpedo",	 				["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-torpedo.png", 		["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "BurgerShot Torpedo" },
	["rimjob"] 		 				 = {["name"] = "rimjob",  	     				["label"] = "Rim Job",	 				["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-rimjob.png", 		["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "BurgerShot Donut" },
	["creampie"] 		 			 = {["name"] = "creampie",  	     			["label"] = "Creampie",	 				["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "creampie.png", 			["created"] = nil,		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "BurgerShot Apple Pie" },
	["cheesewrap"] 					 = {["name"] = "cheesewrap", 					["label"] = "Cheese Wrap", 	     		["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-chickenwrap.png", 	["created"] = nil,		["unique"] = false,   	["useable"] = true,   	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "BurgerShot Goat Cheese Wrap" },	
	["chickenwrap"] 				 = {["name"] = "chickenwrap", 					["label"] = "Chicken Wrap", 	    	["weight"] = 100, 		["decay"] = 0.1,		['hunger'] = math.random(20, 30),	["type"] = "item", 		["image"] = "burger-goatwrap.png", 		["created"] = nil,		["unique"] = false,   	["useable"] = true,   	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "BurgerShot Chicken Wrap" },
```
```lua
-- UWU CATCAFE
    ["uwupancake"] = {["name"] = "uwupancake", ["label"] = "uWu Savory Pancake", ["weight"] = 100, 		["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwupancake.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Korean savory pancake made with scallions."}, 
    ["uwucupcake"] = {["name"] = "uwucupcake", ["label"] = "uWu Cupcake", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwucupcake.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Sugar Kitty Cupcake!"}, 
    ["uwuvanillasandy"] = {["name"] = "uwuvanillasandy", ["label"] = "uWu V-Icecream Sandy", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwuvanillasandy.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Sweet Vanilla Biscuit filled with Icecreamy!"}, 
    ["uwuchocsandy"] = {["name"] = "uwuchocsandy", ["label"] = "uWu C-Icecream Sandy", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwuchocsandy.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Sweet Chocolate Biscuit filled with Icecreamy!"}, 
    ["uwubudhabowl"] = {["name"] = "uwubudhabowl", ["label"] = "uWu Budha Bowl", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwubudhabowl.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Bowl of nourishment and balance."}, 
    ["uwusushi"] = {["name"] = "uwusushi", ["label"] = "uWu Sushi", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwusushi.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Designed as a window to your soul."}, 
    ["uwumisosoup"] = {["name"] = "uwumisosoup", ["label"] = "uWu Miso Soup", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwumisosoup.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "Fungus never tasted so good!"}, 
    ["uwubentobox"] = {["name"] = "uwubentobox", ["label"] = "uWu Bento Box", ["weight"] = 100,  ["decay"] = 0.1, ['hunger'] = math.random(20, 30),	["type"] = "item", ["image"] = "uwubentobox.png",  ["created"] = nil, ["unique"] = false, ["useable"] = true, ["shouldClose"] = true, ["combinable"] = nil, ["description"] = "An uWu Selection with a surprise!"},
```
```lua
--Diner Addon
	["cheese_burger_fries"] 		= {["name"] = "cheese_burger_fries",  	     ["label"] = "chicken caesar wrap",	 	["weight"] = 200, 		["type"] = "item", 		["image"] = "cheese_burger_fries.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["chicken_caesar_wrap"] 		= {["name"] = "chicken_caesar_wrap",  	     ["label"] = "chicken caesar wrap",	 	["weight"] = 200, 		["type"] = "item", 		["image"] = "chicken_caesar_wrap.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["greek_veggie_wrap"] 			= {["name"] = "greek_veggie_wrap",  	     ["label"] = "greek veggie wrap",	 	["weight"] = 200, 		["type"] = "item", 		["image"] = "greek_veggie_wrap.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["spicy_chicken_wrap"] 			= {["name"] = "spicy_chicken_wrap",			 ["label"] = "spicy chicken wrap",		["weight"] = 200,		["type"] = "item",		["image"] = "spicy_chicken_wrap.png",		["unique"] = false, 	["useable"] = true,		["shouldClose"] = true,	    ["combinable"] = nil,	["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["chicken_stips"] 				= {["name"] = "chicken_stips", 				 ["label"] = "chicken stips", 	     	["weight"] = 200, 		["type"] = "item", 		["image"] = "chicken_stips.png", 			["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["french_toast_bacon"] 			= {["name"] = "french_toast_bacon", 		 ["label"] = "french oast bacon", 	    ["weight"] = 200, 		["type"] = "item", 		["image"] = "french_toast_bacon.png", 		["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["grilled_cheese_fries"] 		= {["name"] = "grilled_cheese_fries",  	     ["label"] = "grilled cheese fries",	["weight"] = 200, 		["type"] = "item", 		["image"] = "grilled_cheese_fries.png", 	["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["pbj"] 						= {["name"] = "pbj",  	     				 ["label"] = "pbj",	 		        	["weight"] = 200, 		["type"] = "item", 		["image"] = "pbj.png", 						["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["scrambled_egg"] 				= {["name"] = "scrambled_egg",  	     	 ["label"] = "scrambled egg",	 		["weight"] = 200, 		["type"] = "item", 		["image"] = "scrambled_egg.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["sirloin_burger"] 				= {["name"] = "sirloin_burger",  	     	 ["label"] = "sirloin burger",	 		["weight"] = 200, 		["type"] = "item", 		["image"] = "sirloin_burger.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["steakncheese"] 				= {["name"] = "steakncheese",				 ["label"] = "steak n cheese",			["weight"] = 200,		["type"] = "item",		["image"] = "steakncheese.png",				["unique"] = false, 	["useable"] = true,		["shouldClose"] = true,	    ["combinable"] = nil,	["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["bacon_cheese_fries"] 			= {["name"] = "bacon_cheese_fries", 		 ["label"] = "bacon cheese fries", 	    ["weight"] = 200, 		["type"] = "item", 		["image"] = "bacon_cheese_fries.png", 		["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
	["hot_wings"] 				    = {["name"] = "hot_wings", 					 ["label"] = "hot wings", 	     		["weight"] = 200, 		["type"] = "item", 		["image"] = "hot_wings.png", 				["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "changeme", ['hunger'] = math.random(20, 30) },
```
```lua
-- Food Ingredients
	["chicken_strips_raw"] 			= {["name"] = "chicken_strips_raw",  ["label"] = "Chicken Strips Raw",	 	["weight"] = 200, 		["type"] = "item", 		["image"] = "chicken_strips_raw.png", 	["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Chicken Strips Raw" },
	["burger_bun"] 					= {["name"] = "burger_bun",  	     ["label"] = "Burger Bun",	 			["weight"] = 200, 		["type"] = "item", 		["image"] = "burger_bun.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Burger bun" },
	["hot_sauce"] 					= {["name"] = "hot_sauce",  	     ["label"] = "Hot Sauce",	 			["weight"] = 200, 		["type"] = "item", 		["image"] = "hot_sauce.png", 			["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Hot sauce" },
	["bacon_pieces"] 				= {["name"] = "bacon_pieces",		 ["label"] = "Bacon Pieces",			["weight"] = 200,		["type"] = "item",		["image"] = "bacon_pieces.png",			["unique"] = false, 	["useable"] = true,		["shouldClose"] = true,	    ["combinable"] = nil,	["description"] = "Bacon pieces" },
	["eggs"] 				   	 	= {["name"] = "eggs", 				 ["label"] = "Eggs", 	     			["weight"] = 200, 		["type"] = "item", 		["image"] = "eggs.png", 				["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "Eggs" },
	["jam"] 				    	= {["name"] = "jam", 				 ["label"] = "Jam", 	     			["weight"] = 200, 		["type"] = "item", 		["image"] = "jam.png", 					["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "Jam" },
	["peanut_butter"] 				= {["name"] = "peanut_butter",  	 ["label"] = "Peanut butter",	 		["weight"] = 200, 		["type"] = "item", 		["image"] = "peanut_butter.png", 		["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Peanut butter" },
	["bread"] 						= {["name"] = "bread",  	     	 ["label"] = "Bread",	 		        ["weight"] = 200, 		["type"] = "item", 		["image"] = "bread.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Bread" },
	["fries"] 						= {["name"] = "fries",  	     	 ["label"] = "Fries",	 				["weight"] = 200, 		["type"] = "item", 		["image"] = "fries.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Fries" },
	["veggie"] 						= {["name"] = "veggie",  	     	 ["label"] = "Veggies",	 				["weight"] = 200, 		["type"] = "item", 		["image"] = "veggie.png", 				["unique"] = false, 	["useable"] = true, 	["shouldClose"] = true,   	["combinable"] = nil,   ["description"] = "Veggies" },
	["sirloin_steak"] 				= {["name"] = "sirloin_steak",		 ["label"] = "Sirloin steak",			["weight"] = 200,		["type"] = "item",		["image"] = "sirloin_steak.png",		["unique"] = false, 	["useable"] = true,		["shouldClose"] = true,	    ["combinable"] = nil,	["description"] = "Sirloin steak" },
	["steak"] 				    	= {["name"] = "steak", 				 ["label"] = "Steak", 	     			["weight"] = 200, 		["type"] = "item", 		["image"] = "steak.png", 				["unique"] = false,   	["useable"] = true,   	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "Steak" },
	["salad"] 				    	= {["name"] = "salad", 				 ["label"] = "Salad", 	     			["weight"] = 200, 		["type"] = "item", 		["image"] = "salad.png", 				["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "Salad" },
	["wraps"] 				    	= {["name"] = "wraps", 				 ["label"] = "Wraps", 	     			["weight"] = 200, 		["type"] = "item", 		["image"] = "wraps.png", 				["unique"] = false,   	["useable"] = true,   	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "Wraps" },
	["wrap"] 				    	= {["name"] = "wrap", 				 ["label"] = "Wrap", 	     			["weight"] = 200, 		["type"] = "item", 		["image"] = "wrap.png", 				["unique"] = false,   	["useable"] = true,    	["shouldClose"] = true,     ["combinable"] = nil,   ["description"] = "Wrap" },
```
```lua	
-- Brownies
	['brownie1'] = { ['name'] = 'brownie1', ['label'] = 'Brownie', 			['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie1.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
	['brownie2'] = { ['name'] = 'brownie2', ['label'] = ' Mint Brownie', 	['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie2.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
	['brownie3'] = { ['name'] = 'brownie3', ['label'] = ' Toffee Brownie',  ['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie3.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
	['brownie4'] = { ['name'] = 'brownie4', ['label'] = 'Lemon Brownie', 	['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie4.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
	['brownie5'] = { ['name'] = 'brownie5', ['label'] = 'Choc Brownie', 	['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie5.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
	['brownie6'] = { ['name'] = 'brownie6', ['label'] = 'Brownie', 			['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie6.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
	['brownie7'] = { ['name'] = 'brownie7', ['label'] = 'Brownie', 			['weight'] = 200, ['type'] = 'item', ['image'] = 'brownie7.png', ['unique'] = false, ['useable'] = true, ['shouldClose'] = true, ['combinable'] = nil, ['description'] = 'Brownie.' },
```
```lua
