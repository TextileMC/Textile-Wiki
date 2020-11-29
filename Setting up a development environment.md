# Welcome to the Textile-Wiki!
The Textile-Wiki is a wiki for all things related to Infdev and TextileMC's APIs / Code.
### WARNING: This is not meaning to be an introduction to general modding concepts.

## Setting up a development environment
To setup a development environment for Infdev mods using the Fabric Loader, download or clone [TextileMC's Example Mod](https://github.com/TextileMC/textile-example-mod). This is a generic base for every mod and should be used over manually creating a project.

Run the command `gradlew.bat genSources` if you are on Windows, or `./gradlew genSources` for MacOS and Linux variants.
This will generate the Minecraft Infdev sources for modding use in your gradle caches.

The next step depends on your IDE of choice:
 * `gradlew.bat idea` or `./gradlew idea` (Intellij IDEA)
   * For IDEA, import the Gradle project. Fabric no longer supports setting up the project using the command line.
 * `gradlew.bat eclipse` or `./gradlew eclipse` (Eclipse IDE)
 * `gradlew.bat vscode` or `./gradlew vscode` (VSCode IDE)

After importing the project, You may start coding immediately.
