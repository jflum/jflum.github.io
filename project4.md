[Back to Portfolio](./)

Simple UDP Client
=================

-   **Class:** CSCI 332 - Applied Networking
-   **Grade:** A
-   **Language(s):** C++
-   **Video Demonstration:** [Watch on YouTube](https://youtu.be/H_QGWAo7pLw)
-   **Source Code Repository:** [features/mastering-markdown](https://guides.github.com/features/mastering-markdown/)  
    (Please [email me](mailto:example@csustudent.net?subject=GitHub%20Access) to request access.)

## Project description

Provided the corresponding User Datagram Protocol (UDP) server program, the Simple UDP Client allows for the efficient transmission of files over a specified network (via a user-defined port and IP address). Files are split into binary data blocks of 1000 bytes, packaged, and sent to the server where they are then reassembled, producing an output file identical to the original.

## How to compile and run the program

```bash
cd ./FatalException
javac ./src/fatalexception/*.java -d ./
java fatalexception/FatalException
```

## UI Design

Upon launching the game, players are greeted by a foreboding title screen (Fig. 1), followed immediately by the main menu after any key press. Here, the user can select to begin a new quest, view the readme or credits, or simply exit the program. First, let’s select the readme option (Fig. 2) in order to gain an orientation to the various gameplay mechanics, as well as receive some strategic advice.

![screenshot](images/p1f1.jpg)  
*Figure 1. Fatal Exception's launch screen.*

## Additional Considerations

Minimum requirements: GNU Compiler Collection (GCC) version 9.3.0.
```bash
sudo apt update
sudo apt install build-essential
```

[Back to Portfolio](./)
