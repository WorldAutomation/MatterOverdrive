# Matter Overdrive

![alt tag](https://raw.githubusercontent.com/simeonradivoev/MatterOverdrive/master/MatterOverdriveLogo.png)
<!--
<h2 align="center">
<a href='https://mo.simeonradivoev.com/'>Website</a> | 
<a href='https://mo.simeonradivoev.com/category/gettingstarted/'>Getting Started</a> |
<a href='https://mo.simeonradivoev.com/category/faq/'>FAQ</a> | 
<a href='https://mo.simeonradivoev.com/download_category/downloads/'>Downloads</a> | 
<a href='https://mo.simeonradivoev.com/builds/'>Dev Builds</a>
</h2>
-->

[![Build Status](https://travis-ci.org/simeonradivoev/MatterOverdrive.svg?branch=1.8.9)](https://travis-ci.org/simeonradivoev/MatterOverdrive)

## Current Developer: WorldAutomation.Net

## Table of Contents
* [About](#about)
* [Features](#features)
* [Contacts](#contacts)
* [Issues](#issues)
* [Building](#building)

## About
Matter Overdrive is a Minecraft mod inspired by the popular Sci-fi TV series Star Trek. It dwells in the concept of replicating and transforming one type matter into another.
Although it may seem overpowered, Matter Overdrive takes a more realistic approach and requires the player to build a complex system before even the simplest replication can be achieved.

## Features
* [Matter Scanner](https://mo.simeonradivoev.com/items/matter_scanner/), for scanning matter patterns for replication.
* [Replicator](https://mo.simeonradivoev.com/items/replicator/), for transforming materials.
* [Decomposer](https://mo.simeonradivoev.com/items/decomposer/), for breaking down materials to basic form.
* [Transporter](https://mo.simeonradivoev.com/items/transporter/), for beaming up.
* [Phaser](https://mo.simeonradivoev.com/items/phaser/), to set on stun.
* [Fusion Reactors](https://mo.simeonradivoev.com/fusion-reactor/) and [Gravitational Anomaly](https://mo.simeonradivoev.com/items/gravitational_anomaly/)
* Complex Networking for replication control.
* Star Maps, with Galaxies, Stars and Planets
* [Androids](https://mo.simeonradivoev.com/android-guide/), become an Android and learn powerful RPG like abilities, such as Teleportation and Forefield Shields.


![Matter Overdrive Blocks and Items](https://media-elerium.cursecdn.com/attachments/210/237/main_screenshot.png)

## Issues
If you have any crashes, problems or suggestions just open a [new Issue](https://github.com/simeonradivoev/MatterOverdrive/issues/new).
If your crash or problem was fixed, but is not yet released as a public download you can always download the latest [Dev Build](https://mo.simeonradivoev.com/builds/).

## Building
1. Clone this repository via 
  - SSH `git clone git@github.com:simeonradivoev/MatterOverdrive.git` or 
  - HTTPS `git clone https://github.com/simeonradivoev/MatterOverdrive.git`
2. Setup workspace (This currently does not work due to a ping timeout on rx14's mvn server.)
  - Decompiled source `gradlew setupDecompWorkspace`
  - Obfuscated source `gradlew setupDevWorkspace`
  - CI server `gradlew setupCIWorkspace`
3. Build `gradlew build`. Jar will be in `build/libs`
4. For core developer: Setup IDE
  - IntelliJ: Import into IDE and execute `gradlew genIntellijRuns` afterwards
  - Eclipse: execute `gradlew eclipse`
  - Don't forget to install [Lombok](https://projectlombok.org)
