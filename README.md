# Virtual Pet Game

Welcome to **Virtual Pet**, a Java-based desktop game where you take care of an adorable animal companion! Your job is to keep your pet healthy, happy, well-fed, and well-rested by feeding it, playing with it, taking it to the vet, and more. The pet's mood changes dynamically, and neglect can lead to sickness or even death—so stay attentive!

##  Features

- Choose from three pets: **Dog**, **Duck**, or **Sheep**—each with unique decay rates
- Manage pet stats: **Health**, **Happiness**, **Sleep**, and **Fullness**
- Feed your pet and give it gifts from your inventory
- Take your pet to the vet or exercise with it to boost health
- Built-in cooldowns and timed effects
- Background music selection and volume control
- Save/load system for up to 3 save slots
- Parental controls with password(You will set a password upon first entry), playtime restriction, and pet revival
- Tutorial screen for new users

---

##  Required Libraries & Tools

| Library / Tool         | Version            | Purpose                              |
|------------------------|--------------------|--------------------------------------|
| Java JDK               | 24                | Core language and compiler           |
| Gson                   | 2.10.1            | JSON serialization/deserialization   |
| JUnit Jupiter          | 5.8.2             | Unit testing                         |
| javax.swing            | Built-in (JDK)    | GUI components                       |

---

##  Build Instructions(option)

1. **Install Java Development Kit (JDK 24)**
   - Download: https://www.oracle.com/java/technologies/javase-downloads.html

2. **Install Gson**
   - Download `gson-2.10.1jar` or later from https://github.com/google/gson
   - Place it in your project folder
   
3. **Set up the project**
   - Open the project in any Java development IDE(e.g. Eclipse)
   - Place all `.java` files in the same folder
   - Ensure any resource folders are correctly placed
   
4. **Install JUnit 5**
   - Right-click project > Build Path > Add Library > JUnit > JUnit 5
   - Ensure all `.jar` files in the same folder
   
5. **Compile the source code**
   - Open terminal
   - Navigate to the root of your project
   - Run the following command
```bash
javac -cp "gson-2.10.1.jar;lib/*;out" -d out src/*.java
java -cp "gson-2.10.1.jar;out" Main
```
## run
run the VirtualPets.exe with resources folder


##  Resources & Attributions
- Pet images(dog, duck, sheep) were sourced from https://www.spriters-resource.com/
- Background musics(music1, music2, music3) were sourced from https://pixabay.com/
- Background image were sourced from https://www.freepik.com/
- Icons used in GUI were sourced from https://www.flaticon.com/
