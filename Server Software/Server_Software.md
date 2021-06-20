# Introduction
The server software, also tipically known as a jar, is the file that you download and run to start the server. The server software determines how the server works, what external things it will load, what version of minecraft the server will be, and more. Picking the right software for a project is always one of the first steps of development, as it can completely change things for better or worse. 

# Types of server software.
From Bukkit based to Forge, there are many different types of server software you can run, each with its own advantages and disadvantages. This will go over the main types you will see. The main types of server software you can find will be listed below.

- Vanilla
- Bukkit
- Forge
- Fabric
- Glowstone
- Sponge
- Minestom
- Forge/Bukkit hybrids

## I dont really care about the differences? Just tell me what I should pick!
If you want something that is drag and drop with a good amount of reliability, performance, and features, there is nothing better than Paper. 


## Vanilla

Vanilla software is the same .jar you can download from minecraft.net in their release notes. It's generally the laggiest option, but can be useful for certain applications such as snapshot servers (if you have a beefy CPU). These types of servers often make use of datapacks and chains of command blocks in order to do some of the things done with other backends, such as rudimentary anticheats and certain mechanics. A piece of software known as Vanillacord is able to patch a vanilla .jar so it's able to properly handle IP forwarding from Bungeecord or Waterfall proxies, however it may introduce some side effects in later versions. 

## Bukkit Based

The bukkit based server softwares are some of the most common, as they are very versatile. Bukkit based server software have the capability to load plugins made using the Bukkit API to expand what the server is capable of doing. Plugins range from gameplay content to anticheats. Most Bukkit server software also has modified the game with what are called patches. Patches are extra code put into the server software to further extend its capabilities. Most of the patches are for performance improvements or for bug fixes. A list of all Bukkit based server software can be found below

- CraftBukkit
- Spigot
- Paper
- Tuinity
- Purpur
- Airplane
- Yatopia

Craftbukkit - CraftBukkit is the most barebones server software that you can use except for Vanilla itself. It has no extra bells and whistles.
			  	It can run plugins, and not much else. It performs terribly compared to other options, use only when others will not work.
			  	
Spigot - Spigot is the CraftBukkit jar with a few extras added on. It has basic performance improvements and basic config settings. Nothing to fancy.
			While the performance is better than CraftBukkit, it leaves much to be desired. 

Paper - Paper is the go-to Server Software for many servers. A modified version of Spigot, it is Rock Stable, and performs much better. Paper's config
        ontop of spigot can configure most things. Runs certain things asyncronously for performance. The definition of "drag and drop".

Tuinity - Tuinity is a version of Paper used to add more Performance Patches. Tuinity is designed for higher playercount servers, and performs better under those circumstances.
		    While not unstable, Paper is reccomended unless you hit 30+ players. Reccomended.

Purpur - Purpur is a modified version of Paper designed to add extra gameplay affecting config options and settings, such as rideable mobs, and a customizable F3 Brand.
			Purpur also incorporates much of what Tuinity does for performance, however it is not based off of Tuinity. 
			
			
Airplane - Airplane is the absolute pinnacle of minecraft server performance. Designed for very high playercounts (100+), it runs amazing. However is overkill for most users.
				Other than that, Airplane is build on-top of Tuinity. 


Yatopia - Yatopia is built ontop of Tuinity and Purpur. Yatopia is much faster but at a cost. It is very unstable and has been known to corrupt worlds and other such things.
			The developers have also been known to not take well to advice or criticism. Only available for 1.16.5 and below as Yatopia was discontinued June 19th 2021.

## Forge

Forge is a very popular mod framework which can run both client-side and server-side.

## Fabric

Fabric is another very popular mod framework which runs on both client-side and server-side. There are numerous performance-improving additions for Fabric, see [this resource](https://github.com/comp500/fabric-serverside-mods) for a full list of Fabric server-side mods that may come in handy.

## Glowstone

TODO

## Sponge

TODO

## Minestom

Minestom is a server backend for **advanced users**, as it does not have a downloadable .jar file. Instead, one must compile Minestom itself to run it. It provides basic implementations of the packet protocol, but besides that and some rudimentary components it's about as bare-bones as a server backend can be functionality-wise. Useful for applications where substantial changes beyond what plugins or mods are capable of are needed. The developer utilizing Minestom needs to specify every single mechanic they want to include. Chests for example are not considered to have inventories while on Minestom, unless you implement an inventory system. Not recommended for beginners.

Minestom does have a vanilla-reimplementation fork, however it's not production-ready at all and most likely won't be for a very long time.

## Forge/Bukkit Hybrid

Forge/Bukkit Hybrid backends are some of the weirdest backends out there. They're attempts to implement both mods AND bukkit-api plugins. As a consequence, most are not as stable as other forms of backend, and may suffer from performance issues. Not recommended unless you have a very specific need.
