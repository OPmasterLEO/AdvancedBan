# AdvancedBan+


Bukkit- Folia support & BungeeCord-Plugin at once <br>
Check out our [Spigot-Page](https://www.spigotmc.org/resources/advancedban.8695/) for more  information!

![Minecraft Version 1.7-1.13](https://img.shields.io/badge/supports%20minecraft%20versions-1.7--1.16-brightgreen.svg)
![license GPL-3.0](https://img.shields.io/badge/license-GPL--3.0-lightgrey.svg)
[![CircleCI](https://circleci.com/gh/DevLeoko/AdvancedBan.svg?style=svg)](https://circleci.com/gh/DevLeoko/AdvancedBan)

_Coded by Leoko_ 

## Description
AdvancedBan= is an fork of an AdvancedBan. All-In-One Punishment-System with warns, tempwarns, mutes, tempmutes, bans, tempbans, ipbans and kicks.
There is also a PlayerHistory so you can see the players past punishments and 
the plugin has configurable Time & Message-Layouts which automatically calculate and increase the Punishment-Time for certain reasons.
AdvancedBan provides also a full Message-File so you can change and translate all messages & a detailed config-file with a lot of useful settings.
This is a BungeeCord & Bukkit/Spigot-Plugin in one and it supports MySQL and Local-File-Storage.

## API
To use the API you need to add AdvancedBan to your project and declare it as a dependency in the plugin.yml.

Add AdvancedBan to you project by adding the AdvancedBan.jar to your build-path or as a:
#### Maven dependency in your pom.xml

Example Usage from Jitpack:
```xml
<repositories>
  <repository>
    <id>jitpack.io</id>
    <url>https://jitpack.io</url>
  </repository>
</repositories>
...
<dependency>
  <groupId>com.github.DevLeoko</groupId>
  <artifactId>AdvancedBan</artifactId>
  <version>v2.3.0</version>
</dependency>
```
Note: Jitpack also supports dependencies for gradle!

[AdvancedBan on Jitpack](https://jitpack.io/#DevLeoko/AdvancedBan)


You can use this API for both Spigot and Bungeecord plugins.
Check out the [Java Docs](https://devleoko.github.io/AdvancedBan/) to get started.
