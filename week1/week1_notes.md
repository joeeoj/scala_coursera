Installation
============

1. Install [Java SDK 13](https://www.oracle.com/technetwork/java/javase/downloads/index.html)
2. Add java bin to your PATH if necessary. In my case java installed to `/usr/bin/java` and `usr/bin` was already on my path
    * For example: `export PATH="/PATH/TO/YOUR/jdk11-VERSION/bin:$PATH"`
3. Install sbt with homebrew: `$ brew install sbt`
4. Install IntelliJ CE
5. When it opens up go to Configure -> Plugins and install the Scala plugin and restart the IDE

The tutorial suggests opening a Scala Worksheet which was not available in my IDE. I Googled around and found [this solution](https://stackoverflow.com/a/36870897) on stackoverflow. It explains that you need to right click on the project on the left-hand side of the screen (ExampleProject for me) and select `Add Framework Support` then add Scala.