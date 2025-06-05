````markdown
# Remote_Control

## Description
Didactic Java example of object-oriented programming. This project simulates a remote control (`ControleRemoto`) that implements an interface (`Controlador`) with operations such as power on/off and volume adjustment.

## How to Run

1. Install Java 8+ and Maven.
2. Open your terminal and navigate to the project folder.
3. To compile and run using Maven, execute:
   ```bash
   mvn clean compile exec:java -Dexec.mainClass="com.mycompany.main.MAIN"
````

4. Alternatively, build the JAR file and run:

   ```bash
   mvn package
   java -cp target/Remote_Control.jar com.mycompany.main.MAIN
   ```
5. Check the console output to see the remote control turn on and display the volume status menu.

## Features

* **Controlador**: Interface defining methods to power on/off, open/close menu, increase/decrease volume, mute/unmute, play, and pause.
* **ControleRemoto**: Implementation storing current state (on/off, volume, playing) and executing interface-defined actions.
* **Main**: Example usage that turns on the remote and displays the menu.

## Technologies

* Java (JDK)
* Maven (build tool)

## Learnings

* Interfaces and abstract method implementation
* Attribute encapsulation
* Use of default constructors
* Flow control in Java

```

Quer que eu faça a versão em português desse Markdown também?
```
