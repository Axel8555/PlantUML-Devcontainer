# PlantUML-Devcontainer

Preconfigured devcontainer for running PlantUML with VS Code extension support and included examples. Perfect for working with UML diagrams in Dockerized environments.

## Using the PlantUML Extension

The PlantUML extension allows you to generate UML diagrams from text. Below is an explanation of how to use the Alt+D key combination to generate diagrams.

1. **Install the PlantUML Extension**:

- Open Visual Studio Code.
- Go to the Extensions tab (icon of squares in the sidebar).
- Search for "PlantUML" and install the extension developed by "jebbs". You can find it [here](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) or by using the extension ID `jebbs.plantuml`.

1. **Configure PlantUML**:

- Make sure you have Java installed on your system.
- Configure the `java` path in the extension settings if necessary.

2. **Create a PlantUML File**:

- Create a new file with the extension `.puml` or `.plantuml`.
- Write your diagram in the file. For example:

```
@startuml
Alice -> Bob: Test
@enduml
```

3. **Generate the diagram**:

- Save the file.
- Press **`Alt+D`** to generate and preview the diagram.

4. **Export the diagram**:

- You can export the diagram to different formats (PNG, SVG, etc.) using the extension commands.
- Press **`Ctrl+Shift+P`** and type "PlantUML: Export Current Diagram" to choose the export format and location.

With these steps, you can easily create and visualize UML diagrams using the PlantUML extension in Visual Studio Code.
