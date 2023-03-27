# WebFX Maven Archetype


## Overview
Provides a WebFX project template. Prevents the need for the WebFX CLI to be installed alongside a WebFX project. Instead, developers can install this archetype, then generate a new WebFX project from it using the commands below. This archetype will (eventually) allow all WebFX functions to be incorporated into the IDE.


## Usage
### 1. Install the WebFX Maven Archetype to the local Maven repository:

```sh
mkdir -vp webfx-maven-archetype
cd webfx-maven-archetype
git clone https://github.com/webfx-project/webfx-maven-archetype.git .
mvn install
```

### 2. Now build a new WebFX project from the archetype:
```sh
mkdir -vp ~/my-new-webfx-project
cd ~/my-new-webfx-project
mvn archetype:generate -DarchetypeGroupId=dev.webfx -DarchetypeArtifactId=webfx-maven-archetype -DarchetypeVersion=1.0-SNAPSHOT
```
