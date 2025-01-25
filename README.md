# CHIP-8 Emulator

This is a Java-based CHIP-8 emulator built using Gradle. It interprets and executes CHIP-8 programs (ROMs), providing a functional emulator with basic rendering and input handling.

## Features
- Full CHIP-8 instruction set implementation.
- Monochrome graphics rendering.
- Input handling for CHIP-8 key mappings.
- Timer and sound support.
- Modular design for easy testing and extension.
- Breakpoints for debugging

## Requirements
- Java 8 or higher
- Gradle 7 or higher

## Folder Structure
```
Chip8Emulator/
├── build.gradle        # Main Gradle build file
├── settings.gradle     # Gradle settings file
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── chip8/
│   │   │           ├── emulator/
│   │   │           │   ├── Chip8.java           # Main emulator logic
│   │   │           │   ├── Memory.java          # Memory management
│   │   │           │   ├── CPU.java             # CPU and opcode handling
│   │   │           │   ├── Display.java         # Graphics rendering
│   │   │           │   ├── Input.java           # Input handling
│   │   │           │   └── Utils.java           # Utility methods
│   │   └── resources/
│   │       ├── fonts/                          # Optional: CHIP-8 font files (if needed)
│   │       └── roms/                           # Sample ROM files
│   ├── test/
│       ├── java/
│       │   └── com/
│       │       └── chip8/
│       │           └── emulator/
│       │               ├── Chip8Test.java       # Unit tests for Chip8
│       │               ├── MemoryTest.java      # Unit tests for Memory
│       │               └── CPUTest.java         # Unit tests for CPU
│       └── resources/
│           └── testRoms/                        # Test ROMs for validation
└── gradlew             # Gradle wrapper script (Unix)
└── gradlew.bat         # Gradle wrapper script (Windows)
└── gradle/
    └── wrapper/
        ├── gradle-wrapper.jar
        └── gradle-wrapper.properties
```

## Getting Started

 To get started with this project:

 ### Prerequisites
 - Java 17 or higher
 - Gradle (if not using the Gradle wrapper)

### Clone the repository
```
git clone https://github.com/AhteshamulHaque/Chip8Emulator.git
cd Chip8Emulator
```

### Build the project
```
./gradlew build
```

### Run the emulator
```
./gradlew run
```

 ### Run Tests
 To run unit tests for the project, use the following command:
 ```
 gradle test
 ```
