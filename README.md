# WebFX Maven Archetype


## Overview
Provides a WebFX project template. Prevents the need for the WebFX CLI to be installed alongside a WebFX project. Instead, developers can install this archetype, then generate a new WebFX project from it using the commands below. 

This archetype will, in conjuction with the [WebFX-Maven-Plugin](https://github.com/webfx-project/webfx-maven-plugin), allow all WebFX functions to be incorporated into the IDE.


## Usage


### 1. Download the WebFX Maven Archetype:
```sh
mkdir -vp ~/webfx-maven-archetype
cd ~/webfx-maven-archetype
git clone https://github.com/webfx-project/webfx-maven-archetype.git .
```


### 2. Install to the local Maven repository:
```sh
mvn install
```


### 3. Create your WebFX project folder:
```sh
mkdir -vp ~/my-webfx-project
cd ~/my-webfx-project
```


### 4. Build a new, empty WebFX project from the archetype:
```sh
mvn archetype:generate -DarchetypeGroupId=dev.webfx -DarchetypeArtifactId=webfx-maven-archetype -DarchetypeVersion=1.0-SNAPSHOT
```
